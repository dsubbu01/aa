---?color=#000000
# Augmented Analytics

---?color=linear-gradient(180deg, black 50%, white 50%)

@snap[north span-90 text-center text-white text-14]
What is Augmented Analytics?
@snapend

@snap[south span-90 text-center font-montserrat text-black text-08]
Augmented Analytics is a new paradigm in the analytics world that uses **artificial intelligence**, **data science**, and **machine learning** to **automate data preparation** and **discovery**, with the goal of **producing unbiased** and **optimized recommendations**
@snapend

---?color=linear-gradient(90deg, black 50%, white 50%)
@snap[west span-80 text-white text-14]
Purpose?
Why DXC needs to focus on this emerging trend?
@snapend

@snap[north-east span-50 text-center]
#### Challenges faced by customers in implementing analytic solution, because...
@snapend
@snap[south-east span-48 text-05]
- Processes of **going from raw data to insights** largely remains **manual** and is extremely **time consuming**
- Business community is **inundated with huge amount of data** and it is only **getting worse**
- **Data complexity** is on the rise
- **Feature engineering** and **selection of relevant features** is typically a **complex task**
- Business users **struggle to identify the key features** that plays critical role to take best actions
- Analytics tools are evolving and are getting relatively easier to use – however, **analytics process is highly manual and prone to bias**
- Extremely **difficult for users to explore every possible combination/ pattern**
- **Shortage** of expert **data scientists**
@snapend

---?color=linear-gradient(90deg, #5384AD 65%, white 35%)
@title[Add A Little Imagination]

@snap[north-west h4-white]
#### And start presenting...
@snapend

@snap[west span-55]
@ul[list-spaced-bullets text-white text-09]
- You will be amazed
- What you can achieve
- *With a little imagination...*
- And **GitPitch Markdown**
@ulend
@snapend

@snap[east span-45]
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


---?image=assets/img/presenter.jpg

@snap[north span-100 h2-white]
## Now It's Your Turn
@snapend

@snap[south span-100 text-06]
[Click here to jump straight into the interactive feature guides in the GitPitch Docs @fa[external-link]](https://gitpitch.com/docs/getting-started/tutorial/)
@snapend
