# What is **eBPF**
The Enhanced Berkeley Packet Filter
---

### Linux Kernel Requirements

![IMAGE](assets/img/linux_ebpf_support.png)

---?color=linear-gradient(180deg, white 75%, black 25%)
@title[Customize Slide Layout]

### @color[red](Red Hat Support)
https://www.redhat.com/en/blog/introduction-ebpf-red-hat-enterprise-linux-7
eBPF was enabled in Red Hat Enterprise Linux 7.6 
```
# uname -r
3.10.0-940.el7.x86_64
# yum install bcc-tools
```
---?terminal=assets/asciinema/bcc-tools.json&color=#7FDBFF&font=small&title=bcc-tools installation example
---
@snap[north-west span-50 text-center]
#### Platform creation
@snapend
![Conceptual Design](/assets/img/grav-conceptual-design2.png)
@snap[west span-55]
---
@ul[list-spaced-bullets text-09]
- You will be amazed
- What you can achieve
- With a **little imagination**
- And GitPitch Markdown
@ulend
@snapend

@snap[east span-45]
![IMAGE](assets/img/conference.png)
@snapend

@snap[south span-100 bg-black fragment]
@img[shadow](assets/img/conference.png)
@snapend

---

@snap[north-east span-100 text-pink text-06]
Let your code do the talking!
@snapend

```sql zoom-18
CREATE TABLE "topic" (
    "id" serial NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);
ALTER TABLE "topic"
ADD CONSTRAINT forum_id
FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");
```

@snap[south span-100 text-gray text-08]
@[1-5](You can step-and-ZOOM into fenced-code blocks, source files, and Github GIST.)
@[6,7, zoom-13](Using GitPitch live code presenting with optional annotations.)
@[8-9, zoom-12](This means no more switching between your slide deck and IDE on stage.)
@snapend


---?image=assets/img/code.jpg&opacity=60&position=left&size=45% 100%

@snap[east span-50 text-center]
## Now It's **Your** Turn
@snapend

@snap[south-east span-50 text-center text-06]
[Download GitPitch Desktop @fa[external-link]](https://gitpitch.com/docs/getting-started/tutorial/)
@snapend

