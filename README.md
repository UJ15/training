# training

* * *

JAVA 학습 공간 

####백준 알고리즘 문제를 풀며 새로 알게된 부분 기록

### 입출력

#### BufferedReadeer   

##### 많은 양의 데이터를 처리할때 Scanner 보다 월등히 빠르다.   

'''
import java.io.BufferedReader;
import jaca.ip.InputStreamReader;

public class main{
  public statoc void main(String[] args) throws Excetion{  //예외처리
    BufferedReader br = new BufferedReader (new InputStreamReader(System.in));
    
    int a = Integer.parseInt(br.readLine()); // 정수형 한 줄을 입력받을떄
    String s = br.readLine();                 // 문자열을 입력받을 떄
    int b = br.read();                        // 정수형 입력받을 떄
    }
}
'''    
   
