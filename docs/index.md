# about

**Topicalia** is a small publishing experiment for language learning.

It produces short PDF booklets, built around topical lessons and recurring voices. A lesson begins with a word, a scene or a small cultural idea, which then starts to stir the classroom into creative trouble.

> Topicalia is both a course and its commentary, presented as companion student and teacher editions — with a twist.

<div class="grid cards" markdown>

-   :material-book-open-page-variant:{ .lg .middle } __Student edition__

    ---

    Short lessons, voice reactions, class chronicles and appendices for patterns noticed along the way.

-   :material-school:{ .lg .middle } __Teacher edition__

    ---

    Answer keys, teaching notes and comments on how the voices can support discussion.

</div>

<figure markdown="span">
  ![Student PDF pages](assets/screens/japan1-student-edition.png)
  <figcaption>Students watch a small editorial cast react to the lesson from different angles.</figcaption>
</figure>

<figure markdown="span">
  ![Teacher PDF pages](assets/screens/japan1-teacher-edition.png)
  <figcaption>Here is how the teacher gets involved.</figcaption>
</figure>

## current showcase

The current demo edition is:

<div class="grid cards" markdown>

-   :material-ideogram-cjk:{ .lg .middle } __Japan 1__

    ---

    English (UK), B2 level. Five lessons built around Japanese words:
    <em>tsundoku</em>, <em>wabi-sabi</em>, <em>ikigai</em>, <em>omotenashi</em> and <em>kintsugi</em>.

</div>

## how a lesson behaves

A Topicalia lesson is brief by design, but it gets a new life when the main text ends.

```text
lesson
  -> follow-up question
  -> persona reactions
  -> mood reactions
  -> class chronicle
  -> teacher notes on lesson
  -> teacher comments about selected class reactions
```

The main text introduces the topic. The voices then test it, doubt it, rewrite it, overanalyse it or occasionally ignore it.

## the editorial cast

Personas are recurring language critics. Each one notices something different, for example:

<div class="grid cards" markdown>

-   __Ines__
    collects living phrasework and distrusts polished sentences nobody would actually say.

-   __Camila__
    treats memory like an archive and watches how speakers reconstruct the past.

-   __Piotr__
    follows connectors, contrast and the small bridges that stop arguments collapsing.

-   __Rafa__
    pressure-tests language against ordinary life.

</div>

Other voices join the board too: Martha qualifies certainty, Claire retells stories, Samir follows the paths opened by <em>if</em>, and Ethan rewrites until a sentence simply stays with you.

Moods are different. They are brief emotional readings of the same lesson: amused, analytical, bored, confused, impressed, irritated, sad and twisted. They arrive, leave a mark and disappear before anyone asks them to chair a committee.

[Read more about gonzo influence](topicalism/gonzo.md){ .md-button }

## appendices without pretending to be a grammar book

Topicalia marks selected language features inside the content. Those marks can later become appendices: idioms, connectors, grammar areas, lesson types and other patterns that would otherwise remain scattered.

The rule is deliberately freeform. The appendix should collect useful language, not every shiny object that impresses on the language highway.

<figure markdown="span">
  ![Example appendix page from Japan 1](assets/screens/japan1-appendix-highlights.png)
  <figcaption>Highlights become indexes when the dust settles.</figcaption>
</figure>

## what comes next

The next planned direction is **Brasil 1**, a Portuguese edition, which will bring Brazilian words, rhythms and language beauty. _Martha_, who has been waiting politely near the subjunctive, may finally get busy with her beloved grammar structures.

Another possible English edition would zoom in **Japan 1** rather than move on: one whole unit around a single <em>gaman</em> word, viewed through patience, endurance, pressure, silence and the moments when perseverance stops being noble.

## behind the curtain

Topicalia data is stored as HTML fragments and transformed into PDF editions with a small Python/Flask toolchain and WeasyPrint as final renderer. While content development uses AI assistance heavily, the final material is edited, curated and argued with by hand.

## links

- [LinkedIn showcase](https://www.linkedin.com/showcase/topicalia/?viewAsMember=true)
- [LinkedIn project creator](https://www.linkedin.com/in/jacekiwanski/)
- [GitHub](https://github.com/jiwanski)
