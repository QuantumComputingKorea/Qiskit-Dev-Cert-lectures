
# Qiskit-Dev-Cert-lectures

이 노트들은 한국의 Qiskit Community 멤버들이 Qiskit 개발자 자격 시험을 준비할때 도움이 되기 위해 만들어졌습니다. 각 강의 영상들은 개방된 오픈소스 [오픈튜토리얼스](https://www.opentutorials.org/course/4973)에서 확인할 수 있습니다.


이 강의 노트를 커뮤니티 여러분과 함께 만들어가기 원합니다! 기여를 원하시는 분들은 Readme의 "제작 및 검수에 참여한 사람들"에 여러분의 이름을 추가하신 후 컨텐츠를 추가, 수정하여 PR을 보내주세요.

<b>제작 및 검수에 참여한 사람들:</b>

- [신소영](https://github.com/0sophy1)
- [최인호](https://github.com/q-inho)

<b>많은 도움이 된 자료들</b>
1. [Qiskit 공식 교육 자료](http://qiskit.org/learn)
2. [ 공식 샘플 테스트](https://www.ibm.com/training/certification/C0010300)
3. [ James Weaver의 Qiskit 개발자 시험 준비 가이드](https://slides.com/javafxpert/prep-qiskit-dev-cert-exam)
4. [Martin Laforest의 The mathematics of quantum mechanics](http://www.stat.ucla.edu/~ywu/linear.pdf)
5.  [Kory Becker의 Qiskit 개발자 시험 ultimate guide](http://www.primaryobjects.com/2021/09/15/the-ultimate-guide-to-a-quantum-computing-certification-with-qiskit/).
6.  [UIC Quantum Club의 Qiskit 개발자 시험 준비 강의 시리즈](https://www.youtube.com/playlist?list=PL3ZVRVvGqF1cH9SwNKBY-po3HXUPMlghg)
7.  [Bartu Bisgin의 Qiskit 자격증 시험 워크북](https://github.com/bartubisgin/qiskit-certified-exam-workbook)
8.  [Dimple12M의 가이드](https://github.com/dimple12M/Qiskit-Certification-Guide)

이 강의는 선형대수학과 양자역학이 낯선 분들을 위한 두개의 선행 노트와 함께 실질적인 개발자 시험을 준비하는데 도움이 될 다섯 개의 Jupyter notebook으로 구성되어 있습니다.  교재의 구성은 다음과 같습니다.

**Lecture 0: Into the rabbit hole** ([Link](https://github.com/QuantumComputingKorea/Qiskit-Dev-Cert-lectures/blob/main/Lecture0/lecture%200-0%20%20%EC%96%91%EC%9E%90%EC%BB%B4%ED%93%A8%ED%84%B0%EB%A5%BC%20%EC%9C%84%ED%95%9C%20%EC%84%A0%ED%98%95%EB%8C%80%EC%88%98.ipynb))
1. 선형대수
2. 양자역학

**Lecture 1: 게이트와 양자 회로 기본 작성법**

배울 내용
>Single qubit gate ([Link](https://github.com/QuantumComputingKorea/Qiskit-Dev-Cert-lectures/blob/main/Lecture1/lecture%201-0%20-%20%EB%8B%A8%EC%9D%BC%20%ED%81%90%EB%B9%84%ED%8A%B8%20%EA%B2%8C%EC%9D%B4%ED%8A%B8.ipynb))
>
>Multiple qubit gate ([Link](https://github.com/QuantumComputingKorea/Qiskit-Dev-Cert-lectures/blob/main/Lecture1/lecture%201-1%20-%20%EB%8B%A4%EC%A4%91%20%ED%81%90%EB%B9%84%ED%8A%B8%20%EA%B2%8C%EC%9D%B4%ED%8A%B8.ipynb)) 
>
>Barriers and Properties of Quantum Circuit ([Link](https://github.com/QuantumComputingKorea/Qiskit-Dev-Cert-lectures/blob/main/Lecture1/lecture%201-2%20-%20%EB%B0%B0%EB%A6%AC%EC%96%B4%EC%99%80%20%EC%96%91%EC%9E%90%ED%9A%8C%EB%A1%9C%EC%9D%98%20%ED%8A%B9%EC%84%B1.ipynb))
>>Add barriers  
>>Basic info of Quantum Circuit - Depth  
>>Manipulate quantum circuit - extend  
>
>Sample test + lab materials  

**Lecture 2: 양자 회로의 측정과 OpenQasm** ([Link](https://github.com/QuantumComputingKorea/Qiskit-Dev-Cert-lectures/blob/main/Lecture2/lecture%202%20-%20%EC%96%91%EC%9E%90%20%ED%9A%8C%EB%A1%9C%EC%9D%98%20%EC%B8%A1%EC%A0%95%EA%B3%BC%20OpenQasm.ipynb))

배울 내용 

>Measure quantum circuit  
>Syntax  
>How to use classical register  
>OpenQasm  
>>import OpenQasm   
>>export OpenQasm  
>
>Sample test + lab materials  

**Lecture 3: 양자 백엔드(시뮬레이터, 실제 백엔드)에 양자회로 실행하기** ([Link](https://github.com/QuantumComputingKorea/Qiskit-Dev-Cert-lectures/blob/main/Lecture3/Lecture%203%20-%20%EC%96%91%EC%9E%90%20%ED%9A%8C%EB%A1%9C%20%EC%8B%A4%ED%96%89%EA%B3%BC%20%EB%B0%B1%EC%97%94%EB%93%9C.ipynb))

배울 내용  

>circuit execution commands and options   
>Backend options and how to use  
>>Basic Aer  
>>Aer  
>>Real device  
>
>Sample test + lab materials


**Lecture 4: 양자 회로 및 회로의 정보와 실행 결과를 그리고 해석하기** ([Link](https://github.com/QuantumComputingKorea/Qiskit-Dev-Cert-lectures/blob/main/Lecture4/Lecture%204%20-%20%EC%96%91%EC%9E%90%20%ED%9A%8C%EB%A1%9C%20%EC%8B%9C%EA%B0%81%ED%99%94%20%EB%B0%8F%20%EA%B2%B0%EA%B3%BC%20%EB%B6%84%EC%84%9D.ipynb))

배울 내용  
>Visualization  
>>Circuit visualization  
>>Quantum info visualization (QSphere, Bloch vector etc)  
>>Result visualization  
>
>Sample test + lab materials  

**Lecture 5: 유용한 기능들** ([Link](https://github.com/QuantumComputingKorea/Qiskit-Dev-Cert-lectures/blob/main/Lecture5/Lecture%205%20-%20%EC%9C%A0%EC%9A%A9%ED%95%9C%20%EA%B8%B0%EB%8A%A5%EB%93%A4.ipynb))

배울 내용  
>Quantum Information and Auxiliary functions   
>Compare and Construct quantum information  
>Use Qiskit Toolkit  
>Display and use system information  
>Sample test + lab materials  
