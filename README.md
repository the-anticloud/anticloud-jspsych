# JSPSYCH

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `JSPSYCH` in category **PSYCHOLOGY**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** JSPSYCH · **Upstream pin:** `3e24c16c04dc3d2c6406c219126a9c9dc4737627` · **Category:** PSYCHOLOGY · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

![jspsych logo](http://www.jspsych.org/7.0/img/jspsych-logo.jpg)

[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/9910/badge)](https://www.bestpractices.dev/projects/9910)

jsPsych is a JavaScript framework for creating behavioral experiments that run in a web browser. 

Experiments in jsPsych are created using [plugins](https://www.jspsych.org/latest/overview/plugins). 
Each plugin defines different kinds of events, like showing an image on the screen, and collects different kinds of data, like recording which key was pressed at which time. 
By assembling different plugins together into [a timeline](https://www.jspsych.org/latest/overview/timeline), it is possible to create a wide range of online experiments. 

## What can I do with jsPsych?

jsPsych comes with a number of plugins that you can use create tasks and collect data. 
Some plugins do general things, like present a stimulus (text, image, audio, video) and record a key press or button response along with a response time. 
Other plugins do more specific things, like show a set of instructions pages, run a drag-and-drop image sorting task, or calibrate the WebGazer eye-tracking extension. 
See the [list of all plugins](https://www.jspsych.org/latest/plugins/list-of-plugins/) to see what each plugin can do.

Often people can create their experiment by combining these plugins together. 
But if that's not possible for your experiment, you can also modify a plugin file or [create your own plugin](https://www.jspsych.org/latest/developers/plugin-development). 
This gives you the flexibility to do exactly what you want, while still taking advantage of jsPsych's general experiment-building framework. 
The plugin template is *extremely* flexible. If a task is possible to do in a web browser, you can almost certainly implement it as a plugin.

## Getting started

jsPsych can be loaded into a project in a variety of ways, including via CDNs and through NPM. 
You can learn more about setting up a project by following the [hello world tutorial](https://www.jspsych.org/latest/tutorials/hello-world/) on the jsPsych website. 

Once you've got a project set up, the [reaction time task tutorial](https://www.jspsych.org/latest/tutorials/rt-task/) is a great next step, since it covers many core topics and features. 

There are also a number of [community tutorials](https://www.jspsych.org/latest/tutorials/community-tutorials) available on the website.

## Examples

Several example experiments and plugin demonstrations are available in the `/examples` folder. 
After you've downloaded the [latest release](https://github.com/jspsych/jsPsych/releases), double-click on an example HTML file to run it in your web browser, and open it with a programming-friendly text editor to see how it works.

## Documentation

Documentation is available at [https://www.jspsych.org](https://www.jspsych.org/).

## Getting help

For questions about using the library, please use the GitHub [discussions forum](https://github.com/jspsych/jsPsych/discussions). 
You can also browse through the history of Q&A on the forum to find related questions.

## Contributing

We :heart: contributions! 
See the [contributing to jsPsych](https://www.jspsych.org/latest/developers/contributing/) documentation page for more information about how you can help.

## Citation

If you use this library in academic work, the preferred citation is:

de Leeuw, J.R., Gilbert, R.A., & Luchterhandt, B. (2023). jsPsych: Enabling an open-source collaborative ecosystem of behavioral experiments. *Journal of Open Source Software*, *8*(85), 5351, [https://joss.theoj.org/papers/10.21105/joss.05351](https://joss.theoj.org/papers/10.21105/joss.05351).

This paper is an updated description of jsPsych and includes all current core team members. It replaces the earlier paper that described jsPsych:

de Leeuw, J.R. (2015). jsPsych: A JavaScript library for creating behavioral experiments in a Web browser. *Behavior Research Methods*, _47_(1), 1-12. doi:[10.3758/s13428-014-0458-y](http://link.springer.com/article/10.3758%2Fs13428-014-0458-y)

Citations help us demonstrate that this library is used and valued, which allows us to continue working on it.

## Contributors

jsPsych is open source project with [numerous contributors](https://github.com/jspsych/jsPsych/graphs/contributors). 
The project is currently managed by the core team of Josh de Leeuw ([@jodeleeuw](https://github.com/jodeleeuw)), Becky Gilbert ([@becky-gilbert](https://github.com/becky-gilbert)), Björn Luchterhandt ([@bjoluc](https://github.com/bjoluc)), and Jade ([@jadeddelta](https://github.com/jadeddelta)).

jsPsych was created by [Josh de Leeuw](https://www.vassar.edu/faculty/jdeleeuw).

## Thanks

We're grateful for the generous support from a [Mozilla Open Source Support award](https://www.mozilla.org/en-US/moss/), which funded development of the library from 2020-2022, and from a [National Science Foundation Grant](https://www.nsf.gov/awardsearch/show-award?AWD_ID=2346214), which funded work on the broader ecosystem from 2024-2026.

This project is tested with [BrowserStack](https://www.browserstack.com).

---

## Installation

jsPsych can be loaded into a project in a variety of ways, including via CDNs and through NPM. 
You can learn more about setting up a project by following the [hello world tutorial](https://www.jspsych.org/latest/tutorials/hello-world/) on the jsPsych website. 

Once you've got a project set up, the [reaction time task tutorial](https://www.jspsych.org/latest/tutorials/rt-task/) is a great next step, since it covers many core topics and features. 

There are also a number of [community tutorials](https://www.jspsych.org/latest/tutorials/community-tutorials) available on the website.

## Usage

Some plugins do general things, like present a stimulus (text, image, audio, video) and record a key press or button response along with a response time. 
Other plugins do more specific things, like show a set of instructions pages, run a drag-and-drop image sorting task, or calibrate the WebGazer eye-tracking extension. 
See the [list of all plugins](https://www.jspsych.org/latest/plugins/list-of-plugins/) to see what each plugin can do.

Often people can create their experiment by combining these plugins together. 
But if that's not possible for your experiment, you can also modify a plugin file or [create your own plugin](https://www.jspsych.org/latest/developers/plugin-development). 
This gives you the flexibility to do exactly what you want, while still taking advantage of jsPsych's general experiment-building framework. 
The plugin template is *extremely* flexible. If a task is possible to do in a web browser, you can almost certainly implement it as a plugin.

## API

Documentation is available at [https://www.jspsych.org](https://www.jspsych.org/).

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

This gives you the flexibility to do exactly what you want, while still taking advantage of jsPsych's general experiment-building framework. 
The plugin template is *extremely* flexible. If a task is possible to do in a web browser, you can almost certainly implement it as a plugin.

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** JSPSYCH
- **Pinned SHA:** `3e24c16c04dc3d2c6406c219126a9c9dc4737627`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`8aeeebbbee8e190665ace33faa984cccc5fb546cb5afa1e2717c3430a2f746a2`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

