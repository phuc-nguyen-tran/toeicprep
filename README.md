### Toeicprep

## Idea
I got this idea upon my return to Vietnam, where I noticed my dad grinding for his TOEIC exam but to no avail. I decided
to code a project where users can do mock tests on it and kept track of their records via saving their progress reports for
each tests they made.

## Tech Stacks
For this project, I use the MERN stack. The reason I chose MongoDB over indexed database like MySQL or PostgreSQL is that it 
is easier to scale and it allows flexible data type as well as having simpler and readable syntax to query on the database. It
also requires less setup.

## Something I'm proud of
- Helping my dad in someway during his TOEIC preparation. It helps him increasing his score by 30%.
- Learn new tech stacks on the way and comfortable working with it

## Takeaways
- How to use different React library: Redux & Axios. Redux can help with state management and Axios will make API calling much
easier and shorter than the conventional "fetch" method
- Waterfall software developing method

## Challenges
- Authentication is not persistent due to lack of middleware. How to solve: Find out the need for one and write one. Function: collect
the JWT Token and verify it
- Some of my API endpoints only works after the user is authenticated. At first, I just called Axios without any validation on it, so
of course it didn't work. Solution: Add the header object in the param and pass the JWT Token collected from LocalStorage & compare

## Future developments
- I haven't deployed this yet as it can be taken down in the future (Heroku demands fee now :(). I plan to deploy into Docker and Kubernetes
(ongoing, still have to figure out how Docker works)
- Scale the project up. Plans to add Nginx as reverse proxy, and Prometheus & Grafana to monitor the project

That's all - hope you'll enjoy reading this README and my code! Feel free to leave me a message if anything pops up!
