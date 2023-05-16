# ws-reproj

The phrases "The best is the enemy of the good" by Voltaire and
"The only way to go fast is to go well" by Uncle Bob, a
programming guru and co-founder of the Agile Manifesto, are
often overinterpreted in the field of data analysis.
This 2-day workshop (2 hours per day) will start with a simple R
project and demonstrate how to balance speed and robustness
in data analysis. We will explore potential expansions and
requirements and implement incremental solutions that
optimize robustness, reproducibility, maintainability, durability,
shareability, and cooperability while minimizing overall effort.
The workshop's goal is to guide participants from patchworks of
code to well-structured projects, helping them improve their R
skills and workflow for efficient and reproducible data analysis.
You will also discover two great allies: templates, which save
time and effort in setting up complex environments, and
common standards and styles, which simplify project structures
and codes for easier understanding. Whether you are a
beginner or have intermediate experience in R, this workshop
will help you take your data analysis to the next level.

## Dates
Day 1: 2023/05/16 - 5:00 PM -- 7:00 PM (CEST)

Day 2: 2023/05/18 - 5:00 PM -- 7:00 PM (CEST)

## (Free) registration to the event

To participate, click to the [Teams event registration](https://bit.ly/teams-registration-ws-reproj).

## Slides
[https://corradolanera.github.io/ws-reproj/](https://corradolanera.github.io/ws-reproj/)

## Rstudio Cloud
If you cannot access to a local version of Posit RStudio IDE, you can (freely) use the following [RStudio Workspace](https://bit.ly/positcloud-ws-reproj) on Posit Cloud.[^1]

Please note that there are some limitation on the cloud space (i.e., hardware: 0.5 CPU + 1 GB RAM; workshop: no git + no external private folders).

## Day 1

If you have a local installation of Posit RStudio IDE, you can follow each step of the workshop running the following commands, which download a project with the final results ready to go for "the next" step.

Please note: following the workshop, you can start from the first bare project, and continue to aupdate it incrementally up to the last one without needs to download the intermediate stages (and one of the workshop aims is to make you able to do exactly that!).

```r
# install.packages("usethis")
```


- [bare.proj.01](https://github.com/CorradoLanera/bare.proj.01)
 
  ```r
  usethis::use_course("CorradoLanera/bare.proj.01")
  ```

- [foldered.02](https://github.com/CorradoLanera/foldered.02)
 
  ```r
  usethis::use_course("CorradoLanera/foldered.02")
  ```

- [changes.dry.03](https://github.com/CorradoLanera/changes.dry.03)
 
  ```r
  usethis::use_course("CorradoLanera/changes.dry.03")
  ```

- [structure.04](https://github.com/CorradoLanera/structure.04)
 
  ```r
  usethis::use_course("CorradoLanera/structure.04")
  ```

- [private.05](https://github.com/CorradoLanera/private.05)
 
  ```r
  usethis::use_course("CorradoLanera/private.05")
  ```

## Day 2

- > TO BE ADDED

## Code of Conduct

The ws-reproj workshop will be conducted with the [Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html). By participating to the workshop, you agree to abide by its terms.

### Summary View
I am dedicated to providing a welcoming and supportive environment for all people, regardless of background or identity. By participating in this workshop, participants accept to abide by The Carpentries’ Code of Conduct and accept the procedures by which any Code of Conduct incidents are resolved.

**Any form of behaviour to exclude, intimidate, or cause discomfort is a violation of the Code of Conduct.**

In order to foster a positive and professional learning environment we encourage the following kinds of behaviours in all platforms and events:

- Use welcoming and inclusive language

- Be respectful of different viewpoints and experiences

- Gracefully accept constructive criticism

- Focus on what is best for the community

- Show courtesy and respect towards other community members

If you believe someone is violating the Code of Conduct, I ask that you report it to me, [Corrado Lanera](mailto:Corrado.Lanera@ubep.unipd.it) \<Corrado.Lanera@ubep.unipd.it\>, and I will take the appropriate action to address the situation.

> Please note, I am not a Carpentries instructor (yet :-)), but I enforce their Code of Conduct principles in my workshops and events. So, currently, my e-mail address is the best option I can offer to report violation to the Code of Conduct. If, for any reason, you believe the subject of the violation it's me, you can write to the responsible of our administration [Cristiana Vettori](Cristiana.Vettori@ubep.unipd.it) \<Cristiana.Vettori@ubep.unipd.it\> directly to report the incident. Thank you.



[^1]: It needs the creation of a (free) Posit account.

