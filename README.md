C++ 실력 완성 - Fast Campus
요구 사항
Visual Studio 2019
실행 방법
다운로드 or Git Clone
Project/Project.sln 실행
솔루션 탐색기에서 실행할 프로젝션 선택 후 "시작 프로젝트로 설정"
디버그/디버깅 하지 않고 시작(Ctrl + F5)
활용 방법
각 강의마다 프로젝트가 존재합니다. 강의에 사용했던 강의 자료 및 예제들이 각 폴더에 간략하게 정리 되어 있습니다.

함수를 배우기 이전 단계의 프로젝트들은 main 함수에 모든 예제가 포함 되어 있기 때문에 실행 시 단락 별로 적절하게 주석을 활용하기 바랍니다. 각 단락은 {} 중괄호로 구분 됩니다. 주석은 아래와 같은 방법으로 사용할 수 있습니다.

주석 처리
주석 처리를 할 코드(현재 집중하고 싶은 코드 외 다른 코드)들을 선택합니다. 마우스 드래그로 선택하 거나 쉬프트 + 방향키를 활용합니다.
Ctrl + K, Ctrl + C
주석 해제
주석 해제할 코드들을 선택합니다.
Ctrl + K, Ctrl + U
예시
아래와 같이 8진수 출력 단락만 보고 싶은 경우 타 단락들 주석 처리

//{
//    // 16진수 출력 
//   cout << hex << 10 << endl;
//}
{
    // 8진수 출력
    cout << oct << 10 << endl;
}
//{
//    // 10 진수 출력
//    cout << dec << 10 << endl;
//}
