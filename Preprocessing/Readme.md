전처리 진행 상황 공유

### 크롤링 관련
- 📆11/21 : crawling 폴더에 장르 크롤링 한 과정이랑, 크롤링 한 결과 붙여놓은 데이터셋 upload
  - 장르 크롤링 전 , 후 결측치 : 34 ⇨ 10
      
### 전처리 관련
- 📆11/25 : genre imputation 문제 발생 -> 차후 처리 필요, year컬럼과 이를 활용한 era 컬럼 생성, tag 데이터를 movies에 합친 후 전처리
  - 전처리 전, 후 컬럼 변화 : + 'year', 'tag', 'era'
      - era 관련 정보 : 
      Silent Era (Late 19th century to late 1920s): This era marked the early days of cinema when films were made without synchronized sound. Silent movies relied on visual storytelling, often accompanied by live music. Notable directors like Charlie Chaplin and Buster Keaton emerged during this time.

Golden Age of Hollywood (1920s to 1960s): Hollywood's studio system was at its peak during this period. It saw the rise of glamorous studios like MGM, Paramount, and Warner Bros. Movies were characterized by their star-driven plots, genres like musicals, film noir, and the establishment of the Hays Code, a set of censorship guidelines.

New Hollywood (Late 1960s to 1980s): This era marked a departure from traditional studio practices. Filmmakers embraced more experimental and unconventional storytelling, often tackling controversial subjects. Directors like Martin Scorsese, Francis Ford Coppola, and Steven Spielberg gained prominence during this time.

Blockbuster Era (Late 1970s to present): The late 1970s brought a shift towards big-budget, high-concept films designed for mass appeal. Movies like "Jaws" and "Star Wars" set the stage for the blockbuster trend that continues to influence Hollywood today.

Contemporary Era (2000s to present): This period encompasses the digital revolution in filmmaking. Advances in technology have expanded the possibilities for storytelling and special effects. It's characterized by a mix of franchise blockbusters, independent films gaining wider recognition, and the rise of streaming services influencing distribution.
