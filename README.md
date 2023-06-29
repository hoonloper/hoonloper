## 🧑🏻‍💻 Back-End Engineer 

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://komarev.com/ghpvc/?username=yonghoon-jung&color=blueviolet&" />
</a>
<a href="https://blog.naver.com/electron98">
  <img align="center" src="https://img.shields.io/badge/Tech Blog-000000?logo=Bloglovin&logoColor=white" />
</a>

<br />
<br />

<details open>
<summary> 간단소개(Java) </summary>
<div markdown="1">    
  
<img align="right" src="https://github.com/hoonloper/hoonloper/assets/78959175/3ffd7f10-01a5-447c-9aae-41dcdafab0f7" alt="Programmation" width="200" />

```java
public class BackEnd {
  private static final String NAME = "hoonloper";
  private static final int YEARS_OF_EXPERIENCE = 1;
  private static final String[] SKILLS = {"Java", "Spring Boot", "MySQL", "MongoDB"};

  public void introduce() {
    System.out.printf("👋 안녕하세요. %d년차 백엔드 개발자 %s입니다.%n", YEARS_OF_EXPERIENCE, NAME);
    System.out.println("🛠️ 핵심 기술");

    for (String skill : SKILLS) {
      System.out.println("- " + skill);
    }
  }

  public static void main(String[] args) {
    BackEnd yonghoon = new BackEnd();
    yonghoon.introduce();
  }
}
```

</div>
</details>

<details open>
<summary> 간단소개(JavaScript) </summary>
<div markdown="1">       

<img align="right" src="https://user-images.githubusercontent.com/78959175/184319807-064bf4d5-9678-46a3-8a92-8ac31c85f652.gif" alt="Programmation" width="220" />

```typescript
interface Hoonloper {
  readonly name: "hoonloper";
  yearsOfExperience: number;
  skills: string[];
  introduce(): void;
}
const getBackEndEngineer = (name: "hoonloper"): Hoonloper => ({
  name,
  yearsOfExperience: 1,
  skills: ["JS", "TS", "Nuxt", "Nest", "Vue", "MySQL", "MongoDB"],
  introduce() {
    console.log("👋 안녕하세요. " + this.yearsOfExperience + "년차 백엔드 개발자 " + this.name + "입니다.");
    console.log("🛠️ 핵심 기술 -> ", this.skills.join(", "));
  },
});

getBackEndEngineer("hoonloper").introduce();
```

</div>
</details>
