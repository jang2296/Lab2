# Lab2
 ![lab2-0](https://user-images.githubusercontent.com/67464990/144050638-828a6939-e9a6-4ea8-a6f1-b64533f8a379.PNG)
Lab2-0
Echo를 이용해서 hello world를 출력한다.
 ![lab2-1](https://user-images.githubusercontent.com/67464990/144050683-331e2028-2029-41a2-af14-7b2f21ac1b1e.PNG)
Lab2-1
Read를 통해서 숫자를 입력 받으며 seq를 통해서 1~입력한 수로 time이라는 변수를 설정한다. 그 후 for문에서 i의 범위로 time을 사용하여 입력한 수만큼 hello world를 출력한다.
 ![lab2-2](https://user-images.githubusercontent.com/67464990/144050700-f33264b6-4f33-4cca-a387-882efb29668e.PNG)
Lab2-2
Read를 통하여 2개의 수와 연산자를 받고 if문에서 -인지 +인지 확인한다. 연산자를 확인한 후 그에 맞은 값을 계산하여 출력한다.
![lab2-3](https://user-images.githubusercontent.com/67464990/144050710-05d5f4bc-0053-49f3-99f3-1df56f6b2dc6.PNG)
 Lab2-3
Read를 통하여 몸무게와 키를 입력 받는다. BMI 계산에서 키는 m로 계산되므로 cm로 입력된 키의 값을 실수로 변환시키기 보다 몸무게에 10000만을 곱해준다. 또한 비교 값에 18.5라는 실수도 존재하므로 이를 해결하기 위하여 비교 값과 BMI 값에 100을 곱해준다. 그 후 if문에서 산술 비교 연산자를 이용하여 판단한다.
![lab2-4](https://user-images.githubusercontent.com/67464990/144050717-f24e6cac-fba5-48fa-a0b8-6c9768af0fff.PNG)
Lab2-4
Read를 통하여 받은 값을 case문을 통하여 비교한다. |를 활용하여 여러가지 경우를 입력하고 그 중 하나라도 같다면 그에 대한 결과를 출력한다.
![lab2-5](https://user-images.githubusercontent.com/67464990/144050731-6531f253-3131-45e3-9e5b-08ac66539d73.PNG)
Lab2-5
funtion이라는 함수를 만들고 그 안에 리눅스 명령어 ls를 실행시키게 만든다. Eval은 문자열을 명령문으로 인식시키는 것이다. Function 함수를 호출하여 이를 실행시킨다.
![lab2-6](https://user-images.githubusercontent.com/67464990/144050737-12a4333a-1aac-4c6f-af78-eb971a29d9e1.PNG)
Lab2-6
가장 먼저 입력 받은 이름의 파일 혹은 디렉토리가 존재하는지 확인한다. if문에서 만일 입력 받은 이름의 파일이나 폴더가 없다면 mkdir을 통하여 폴더를 생성하고 eval로 생성된 폴더에 들어간다. 그 후 for문을 사용하여 5개의 txt를 생성한다. for문이 끝나고 나면 tar를 이용해서 파일을 압축한다. 파일을 압축할 때 현재의 폴더 내에 있는 모든 것을 압축해야 하므로 *을 사용한다. 그 후 이를 풀어준다.
![lab2-7](https://user-images.githubusercontent.com/67464990/144050746-b170aecc-8c9b-4e00-9aaa-35a67d8c9f9f.PNG)
Lab2-7
dir이라는 변수를 입력 받고 mkdir을 이용해서 변수와 같은 이름의 폴더를 만든다. 그 후 eval을 이용해 폴더로 들어간 후 for문을 활용해 txt와 폴더를 생성한다. 또한 ln -s를 이용하여 대응되는 txt와 폴더를 링크로 연결한다.
![lab2-8](https://user-images.githubusercontent.com/67464990/144050766-8d0c2813-4b2d-48d0-afb8-cf6f1c26741d.PNG)
Lab2-8
이름과 전화번호를 입력 받고 eval로 touch를 사용하여 DB.txt 파일을 만든다. 그 후 >를 사용하여 echo를 통해 결과로 나오는 이름과 전화번호를 DB.txt에 저장한다.
![lab2-9](https://user-images.githubusercontent.com/67464990/144050774-5d8d9bed-b38d-492d-b460-82569475015e.PNG)
Lab2-9
찾을 문자열을 입력 받고 이를 grep을 통하여 찾는다. 이때 grep -n을 이용하여 찾는다. 그 이유는 -n일 경우 입력 받은 문자열과 동일한 것이 있는 줄을 전부 출력하기 때문다.

