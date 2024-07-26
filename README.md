## Кодом о себе

```CSharp
public partial class Personality
{

  /// <summary>
  /// Моя фабричная функция по сборке себя (визуально)
  /// </summary>
  public Personality Create() =>
    new Personality(
      name: "Alexey",
      nickname: "rute_t"
      age: 20,
      hobbies: new Hobbies[6] {
        "Application developing",
        "Math",
        "Chemistry",
        "Chess",
        "Drawing",
        "Guitar playing"
      },
      qualities: new Quality[3] {
        "Overthinking",
        "Overworking",
        "Emo"
      }
    );

  /// <summary>
  /// Для тех кто .......интересуется типологиями
  /// <summary>
  public void MyTypology(out Personality id)
  {
    id.Enneagram.Main = "5w4";
    id.Enneagram.ThreeType = 541;
    id.Young = "IN(F)";
    id.Mbti = "INFJ";
    id.Socionics = "EII";
    id.Psycosophy.BasedInstance.Ident = "LEVF";
    id.Psycosophy.TemporisticInstance.Ident = "VBPN";
    id.Psycosophy.AmatoricInstance.Ident = "ASFE";
  }
}
```

### О себе
Алексей, 20 лет. Скорее всего продолжающий .NET разработчик. Знаю толком ничего, но учусь и разбираюсь. Да, код я написал сам, без нейросетей. Таково правило.
Разбираюсь в:
 - Администрировании Windows,
 - C#, 
 - Visual Basic (6.0 и .NET),
 - Batch
 - T-SQL (потому что работал с Microsoft Azure)
 - ANSI-C
 - Английском (по куче пройденных тестов - уровень b2.1)

### Активно изучаю 
 - ANSI-C - чтобы разбираться с железом и драйверами для ОС.
 - Python - чтобы быстро решать прикладные задачи, требующие много фреймворков. (по возможности переписываю все на C#, если использую это неоднократно)

### Буду изучать и очень долго разбирать
 - Go (golang) - на замену C# в части веба.
 - Rust
 - Haskel

Странный ASD чел, который тормозит абсолютно везде. Я могу затупить и забыть где оставил бутерброд и куда положил холодильник, но
обязательно это вспомню, переработаю и исправлю. Так же наоборот, могу абсолютно случайно вспомнить "как загружаются драйвера в MS-DOS" или что-то хуже.
Я очень люблю ковыряться в историческом хламе. Все что давно устарело, забыто, брошено, это все обязательно попадется мне под руку 
и вместо того, чтобы развиваться вперед и учиться рабоать с актуальными инструментами (например с Postgres SQL), я ковыряюсь в архивах Microsoft и
ищу например анатомию VxD (Virtual Device Driver). Жизнь как-то так сложилась, что я не могу никак распрощаться с продуктами Microsoft.

Мои инструменты:
 - Microsoft Azure
 - Microsoft Visual Studio
 - Microsoft Visual Studio to Office
 - Microsoft Visual C++ compiler
 - Microsoft .NET 6
 - и так далее.

<p>&nbsp;<img align="center" src="https://readmestats.999857.xyz/api?username=AlexeyTolstopyatov&show_icons=true&locale=en&theme=tokyonight" alt="AlexeyTolstopyatov" /></p>

<!--
**AlexeyTolstopyatov/AlexeyTolstopyatov** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
