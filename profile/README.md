# Lebanese Alternative Learning (LAL)

**Free, quality education for every child in Lebanon, online and offline.**

LAL is a Lebanese EdTech NGO based in Beirut. We design inclusive digital learning
solutions that empower educators and learners anytime, anywhere. Our platforms follow
the official Lebanese Ministry of Education curriculum for K-12, in Arabic, French and
English, and they are free to use. No paywall, no freemium tier.

Website: [lal.ngo](https://lal.ngo)

## What we build

| Platform | What it is |
|---|---|
| **Tabshoura** ([tabshoura.com](https://tabshoura.com)) | Student-facing learning platform, Moodle based, web and mobile |
| **LalMoudaress** ([lalmoudaress.com](https://lalmoudaress.com)) | Teacher-facing platform for professional development and resources |
| **Beekee boxes** | Raspberry Pi devices that serve our content to classrooms with no internet |
| **ConsultEd Solutions** ([consultedsolutions.com](https://consultedsolutions.com)) | Our commercial LMS consulting arm. Revenue funds LAL's free education work |
| **Friends of LAL** ([friendsoflal.org](https://friendsoflal.org)) | US 501(c)(3) supporting LAL |

Most of our learning content is H5P interactive activities delivered through Moodle,
built in house by our own teachers, instructional designers, editors and illustrators.

## Impact

Figures below are from our 2026 organisational overview. Please check our latest
annual report for current numbers.

- ~68,000 users
- ~3,200 teachers trained
- 1,281 digital learning units
- 50 school partners
- 54 NGO and INGO partners

## Repositories here

| Repo | What it does |
|---|---|
| [`Slack2Clickup`](https://github.com/Lebanese-Alternative-Learning/Slack2Clickup) | Slack bot that reads IT support requests in plain English and assigns them to the right officer in ClickUp |
| [`moodle-dashboard-data-visualization-block`](https://github.com/Lebanese-Alternative-Learning/moodle-dashboard-data-visualization-block) | Moodle block for dashboard data visualisation |
| [`courses_filter_moodle`](https://github.com/Lebanese-Alternative-Learning/courses_filter_moodle) | Moodle course filtering |
| [`tenantassign-Plugin`](https://github.com/Lebanese-Alternative-Learning/tenantassign-Plugin) | Moodle/IOMAD tenant assignment plugin |
| [`lucians-useful-scripts`](https://github.com/Lebanese-Alternative-Learning/lucians-useful-scripts) | Utility scripts, including one that combines several H5P files into one |
| [`moodleapp`](https://github.com/Lebanese-Alternative-Learning/moodleapp) | Our fork of [moodlehq/moodleapp](https://github.com/moodlehq/moodleapp), used for our branded student app |
| [`friendsoflal`](https://github.com/Lebanese-Alternative-Learning/friendsoflal) | Friends of LAL website |

Licensing is per repository. Moodle plugins and forks follow Moodle's GPL v3.

## How we build

Our constraints come from the students we serve, so they are not negotiable:

- **Arabic RTL first.** Every interface is tested right to left before it ships.
- **Offline capable.** Features degrade gracefully with no connectivity. No external CDNs,
  because the Beekee boxes have no internet at all.
- **Low bandwidth, low spec.** Assume an old phone on a weak connection.
- **Open source by default.** We are an NGO. We prefer open tools and we contribute back.
- **Student privacy.** We do not log or expose student personal data.
- **Small team.** Whatever we build has to stay maintainable by fewer than ten people.

## Working with us

We welcome issues and pull requests on any repo here. If you are an NGO, a school or a
ministry that wants to reuse our work, or a developer who wants to contribute, get in
touch through [lal.ngo](https://lal.ngo).
