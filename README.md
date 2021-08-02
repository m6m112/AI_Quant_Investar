# AI_Quant_Investar
> anaconda 4.10 - 34bit  
> python 3.7 


 ### 초기 세팅 
 1. anaconda 설치 
  - 32bit 가상환경 (키움 API가 32bit에 최적화, 64bit 사용 시 알수없는 에러 발생 가능성 있음)
  - Conda 환경변수 등록 
    ~~~
    (자신의 파일경로)
    (C:\Users\user)\Anaconda3\Scripts 
    (C:\Users\user)\Anaconda3\Library\bin
    ~~~
  - 64bit 설치 시, 32bit로 전환 
    ~~~
    set CONDA_FORCE_32BIT=1                           //32bit로 세팅
    conda create -n py37_32 python=3.7 anaconda       //python 3.7로 py37_32의 가상환경 생성
    activate py37_32                                  //py37_32(가상환경이름) 활성화 
    ~~~
    
