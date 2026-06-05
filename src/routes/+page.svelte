<script>
  import banner from "$lib/assets/banner.jpeg";
  import group from "$lib/assets/group.jpg";
  import {
    Figure,
    H1,
    Link,
    SectionMain,
    Text,
  } from "@computational-biology-aachen/design";
</script>

<svelte:head>
  <title>2022 Watamu Hackathon</title>
</svelte:head>

<SectionMain
  align="start"
  width="90ch"
>
  <Figure
    src={banner}
    alt="Summer school banner"
  />
  <H1 color="primary">2022 Hackathon Watamu</H1>
  <Text>
    In September 2022, Mawazo Institute and RWTH Aachen University jointly
    organized a two-week Summer School in Computational Biology for Sustainable
    Environmental Research, which took place in Watamu, Kenya. I participated as
    a facilitator, keynote speaker, and co-organizer. The school attracted many
    applications but could only accommodate 24 early career research scientists
    from various parts of Africa. These young researchers were equipped with
    core computational modeling skills and data analysis skills using the R and
    Python open source languages. During the two-week program, as facilitators,
    we used numerous teaching methods ranging from interactive talks, hands-on
    programming experience, and discussion panels to our hackathon sessions to
    transfer the aforementioned skills.
  </Text>

  <Figure
    src={group}
    alt="Participants and facilitators of the 2022 Watamu Summer School"
  />

  <Text
    >Founded by the <Link href="https://www.volkswagenstiftung.de/"
      >Volkswagen Foundation</Link
    >.</Text
  >
</SectionMain>
