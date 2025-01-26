## Asteroid Selection

Parameters for Asteroid Selection:
- Types of minerals needed: Iron (steel), Lithium (electronics), Gold (electrical components), Aluminum (building material)
- Distance from asteroid to material dropoff point (the earth's moon for now)
- Asteroid in our current solar system
- Must be possible to mine from (can't be extremely hot/cold, can't be spinning too quickly, can't be traveling too quickly)
Collect Available information of asteroids in the region (region specific in parameter)
- Minor Planet Center - Contains locations of asteroids(https://minorplanetcenter.net/data)
- Must not collide with another object within 2 years

Agent Task:
Based on the asteroid database and the parameters listed, provide a list of top 5 asteroids. In the list provide a measure of how closely it
fits with the parameter (it should be a rating out of 5).
Additionally provide a reasoning for each asteroid being listed.

| Mineral Depth | Composition | Logistics | Kinematics (Temperature, Rotational Velocity, Linear Velocity) | Collision Future |
| --- | --- | --- | --- | --- |

Advanced (Future)
Call upon AI Agent experts from the companies' different business lines to state what challenges their line of work will face for each asteroid in the top 5 list.


[![](https://mermaid.ink/img/pako:eNqdkU-LwjAQxb9KGBF2oUq0rtocFvpP8LasntZ6CG1qi2lSkhR1xe--sdbFwx5k5zTz5r1fYHKGVGYMCORcHtKCKoPWUSKQLX_ja8OULDO0YpylppQCfVBFK2ZlvUWDwXvw4i-Rv2PCvN5C4SaU_GpGS5FLVdFr6m_rg2DXKNoETBt0f1OjT1ZLZbaJaO39PlqZE2fIUlEquVS61XUr-igvOSe9xSKaYexoo-SekZ7rul0_OJSZKci4PjptuN09AML_AzpC0BHmszCOg6cIGONHQtQRPBzHHn6WAA5UzB66zOwvnq-8BEzBKpYAsW1G1T6BRFysjzZGrk4iBWJUwxxQstkVQHLKtZ2aOqOGRSXd2S_-VWsqvqSs7hE7AjnDEQh24ATE9Yaj6cidTO3VRvOxN5leHPhuA3jo3WqG3-bWgb3LD3g_w8g?type=png)](https://mermaid.live/edit#pako:eNqdkU-LwjAQxb9KGBF2oUq0rtocFvpP8LasntZ6CG1qi2lSkhR1xe--sdbFwx5k5zTz5r1fYHKGVGYMCORcHtKCKoPWUSKQLX_ja8OULDO0YpylppQCfVBFK2ZlvUWDwXvw4i-Rv2PCvN5C4SaU_GpGS5FLVdFr6m_rg2DXKNoETBt0f1OjT1ZLZbaJaO39PlqZE2fIUlEquVS61XUr-igvOSe9xSKaYexoo-SekZ7rul0_OJSZKci4PjptuN09AML_AzpC0BHmszCOg6cIGONHQtQRPBzHHn6WAA5UzB66zOwvnq-8BEzBKpYAsW1G1T6BRFysjzZGrk4iBWJUwxxQstkVQHLKtZ2aOqOGRSXd2S_-VWsqvqSs7hE7AjnDEQh24ATE9Yaj6cidTO3VRvOxN5leHPhuA3jo3WqG3-bWgb3LD3g_w8g)


Reflection
Challenges 
- Data on asteroid composition is available, asteroid composition hasn't been a priority of research so little data is available
- Finding the data sources for asteroid information required some time, in addition undertanding the data points required learning what they are and what they mean.
- Determining which parameters would determine the asteroid selection was more complex than I originally thought, I had to take time to research this.
- Deciding on the complexity of the workflow took some time, I wanted to make the task useful however I needed to limit it on how many parameters and inputs would determine the asteroid selection. If this was a real project more time would be allocated for this and it would be in more depth, this is a very simple proof of concept.
- The input size of data needs to be partitioned since the context window is limited for an model at this time.
