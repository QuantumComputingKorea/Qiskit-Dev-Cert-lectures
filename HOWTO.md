# How to install `qiskit==0.2x.x` 

## on Linux x86_64

1. install anaconda and create environment as usual
    ```bash
    conda create -n qiskit-2x python=3.8
    conda activate qiskit-2x
    ```
2. Unlike newer versions, you have to install `Rust` for older versions of qiskit.
    ```bash
    curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
    source $HOME/.cargo/env
    ```
3. Now you can downgrade to older versions of qiskit from source, or `pip`
    ```bash
    pip install -U qiskit==0.2x.x
    ```

4. For this lectures, you would need the followings
    ```bash
    pip install matplotlib==3.4.3 ipywidgets ipykernel pylatexenc seaborn
    ```