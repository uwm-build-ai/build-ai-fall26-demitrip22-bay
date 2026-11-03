# 🐾 Adoption Day

Play the tour
{: .avatar_trigger target="app_tour" }

```yaml
face:
  skin: "#e0ac69"
  hair: full
  hair_color: "#4a3426"
  glasses: none
  wear: shirt
script:
  - do: read
    say: "Welcome to Adoption Day. Pick a campus to see if the weather is good for a dog walk."
  - at: campus_grid
    do: select
    with: Racine
    say: "When you pick Racine, the map moves there and the forecast updates for that campus."
  - at: campus_grid
    do: select
    with: Milwaukee
    say: "Back in Milwaukee, check the forecast for rain and heat before taking the dogs out."
  -   - at: menu
    do: open
    with: Author
    say: "I'm Demitri. I built this in one semester, and I'm proud that one click updates both the map and the forecast.
stories: {}
```
{: .avatar #app_tour size="100" }