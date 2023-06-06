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

## Event
[R/Medicine Virtual Conference 2023](https://events.linuxfoundation.org/r-medicine/), taking place from June 5-9, 2023, in Eastern Daylight Time (EDT, GMT-4).

R/Medicine 2023 Virtual Conference is using [Sched](https://rmed2023a.sched.com/) for the official event schedule & directory.

[Workshop](https://sched.co/1MwSI): Presented live – 3 hours of interactive learning with active coding, taking place June 6, 2023, 11:00am - 2:00pm EDT.


## Registration to the event

To participate:

- [Register now](https://events.linuxfoundation.org/r-medicine/register/).

- [Connect](https://sched.co/1MwSI) to the workshop on [Sched](https://rmed2023a.sched.com/)

- Join the Zoom meeting from there.

## Slides
[https://corradolanera.github.io/ws-reproj/](https://corradolanera.github.io/ws-reproj/)

## Rstudio Cloud
If you cannot access to a local version of Posit RStudio IDE, you can (freely) use the following [RStudio Workspace](https://bit.ly/positcloud-ws-reproj) on Posit Cloud.[^1]

Please note that there are some limitation set on the cloud space (i.e., hardware: 0.5 CPU + 1 GB RAM; workshop: no git + no external private folders).

## Workshop

If you have a local installation of Posit RStudio IDE, you can follow each step of the workshop running the following commands, which download a project with the final results ready to go for "the next" step.

Please note: following the workshop, you can start from the first bare project, and continue to update it incrementally up to the last one without needs to download the intermediate stages (and one of the workshop aims is to make you able to do exactly that!).

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

- [targets.06](https://github.com/CorradoLanera/targets.06)
 
  ```r
  usethis::use_course("CorradoLanera/targets.06")
  ```


## Code of Conduct

Please read and abide by the Code of Conduct, which can be found [here](https://events.linuxfoundation.org/r-medicine/attend/code-of-conduct/). The Code of Conduct is strictly enforced. Speakers especially review this Code of Conduct and are careful to be inclusive in the words and images used during their presentations.


## Inclusive Speaker Orientation Online Course
In collaboration with the National Center for Women in Technology (NCWIT), the Linux Foundation has created an [online course](https://training.linuxfoundation.org/content/inclusive-speaker-orientation) designed to teach the viewer about inclusion, diversity, and unconscious bias. We highly recommend all of our speakers watch the course to learn tips/tools to use when speaking to encourage inclusivity in presentations and messaging. 


## Join the Conversation!  
Be sure to use the official `#RMed23` in your social posts.


## Questions

If you have any questions regarding the event, please don't hesitate to contact [cfp@linuxfoundation.org](mailto:cfp@linuxfoundation.org). 
If you have any question regarding the workshop, please don't hesitate to contact [me](mailto:corrado.lanera@gmail.com).

[^1]: It needs the creation of a (free) Posit account.

