
# 🧭 My app

````tabs
### 🎯 Problem

[My choice](welcome.md)
{: .import bench="true" }

**{= my_project.first.name }** — {= my_project.first.story.replace(my_project.first.character, persona.name or my_project.first.character) }

```yaml
name: Tom
role: Small business owner
goal: Find reliable local help to finish client projects on time.
frustration: Tom has too much work and not enough time to finish everything himself.
story: Tom is a small business owner who struggles to finish all his client projects on time. He needs Gig Board to help him find reliable local workers for small jobs so he can save time and focus on growing his business.
```
{: .persona #persona save="zim.yaml" }

```yaml
product: Gig Board
audience: Small business owners who need extra help.
problem: Small business owners struggle to finish jobs on time.
solution: Gig Board helps them find reliable local workers for small jobs.
```
{: .pitch #pitch save="pitch.yaml" persona="persona" }

### 🗺️ Map and backlog

[My map](#)
{: .runner src="map.md" bench="true" title="" }

```yaml
- { as_a: "", headline: "", i_want: "", so_that: "", value_why: "", tech_note: "" }
```
{: .dataset #backlog }

```csv
my features, read from my space
```
{: .datagrid #backlog_grid source="backlog" save="features.yaml" columns="headline, i_want, business_value, value_why, tech_note" height="260" title="📋 My features" }

### 🙋 Author

[My CV](#)
{: .runner src="../module_01/cv.md" bench="true" }
````
{: .tabs #menu }
