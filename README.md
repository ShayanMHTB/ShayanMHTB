Hi there! I'm Shayan. 👋  
I’m a full-stack developer, problem solver, and curious tinkerer.  
I build high-performance web apps, wire up reliable backends, and keep things elegant and maintainable.

Outside the editor you’ll catch me tuning my dev setup, lifting, reading about the future of computing,  
and dreaming up side-projects I may or may not finish 😅

<!-- Two-column code showcase -->
<table>
  <tr>
    <td width="50%">

      ```javascript
      export const profile = {
        name: "Your Name",
        role: "Full-Stack Developer",
        location: "Your City, Country",
        currentlyAt: "Company",
        website: "https://your-portfolio.com",
        interests: ["AI/ML", "Web3", "IoT", "Quantum"],
        funFacts: [
          "Can debug with podcasts",
          "Never broken prod (intentionally)",
          "Quick fixes → mini refactors"
        ],
        pinned: ["repo-one", "repo-two", "repo-three"]
      };

      console.log(`Welcome to ${profile.name}'s GitHub!`);
      ```

  </td>
  <td width="50%">

    ```python
    from dataclasses import dataclass

    @dataclass(frozen=True)
    class Profile:
        name: str = "Your Name"
        role: str = "Full-Stack Developer"
        location: str = "Your City, Country"
        company: str = "Company"
        website: str = "https://your-portfolio.com"
        interests: tuple = ("AI/ML", "Web3", "IoT", "Quantum")
        fun_facts: tuple = (
            "Can debug with podcasts",
            "Never broken prod (intentionally)",
            "Quick fixes → mini refactors",
        )
        pinned: tuple = ("repo-one", "repo-two", "repo-three")

    me = Profile()
    print(f"Hi, I'm {me.name} — welcome!")
    ```

    </td>

  </tr>
</table>
