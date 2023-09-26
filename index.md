# Introduction to the ELIXIR Software Management Plan

Data Management Plans (DMPs) are a cornerstone of good data management and are now considered a key element of Open Science practices. A DMP describes the data management life cycle for the data to be collected, processed and/or generated within the lifetime of a particular project or activity. Conversely, a Software Management Plan (SMP) can help formalise a set of structures and goals that ensure the software is accessible and reusable in the short, medium and long term. Although it has a management perspective, the main advantage of an SMP is that it provides clear context to the software that is being developed. In that sense, it addresses several aspects of the software development process such as (a) supporting reproducibility and reusability of the software, (b) allowing funding agencies to have a better grasp of the envisioned development process (as well as the achieved milestones), (c) increasing the awareness of the existing community standards that can/should be used, and (d) ensuring that the software can be easily accessed by the wider community.

There are a few flavours of SMPs already available in one form or another. The Software Sustainability Institute (SSI) offers a very detailed checklist that is further complemented by an online [sustainability evaluation service (SES)](https://www.software.ac.uk/resources/online-sustainability-evaluation). Several journals (such as [SoftwareX](https://www.journals.elsevier.com/softwarex) and the [Journal of Open Source Software (JOSS)](https://joss.theoj.org/)) have checklists that are expected to be filled in by the software authors before any submissions addressing most of the key points of an SMP. Finally, there are funding agencies (such as the [Wellcome Trust](https://wellcome.org/)) that expect a plan for the management of research output, including software, in submitted applications. 

A key downside of the aforementioned SMPs is that they tend to be rather complex, occasionally requiring deep technical knowledge of the software development process. In order to address these drawbacks, ELIXIR has designed a simplified version of an SMP, tailored for Life Science oriented projects but still general enough so as to be widely used. The primary goal of the ELIXIR SMP is to encourage wider adoption by Life Science researchers, and be as inclusive as possible to the various levels of technical expertise, while also having an explicit connection to the FAIR principles for Research Software. A common theme in Life Science researchers is the wide differences in background expertise, with the vast majority of researchers being self-taught research software developers. Having an SMP with a relatively low barrier in technical knowledge, while maintaining all the best practices expected in research software development, may both encourage wider adoption of these practices as well as increase the awareness of the multiple aspects involved in research software development.

The overall process that led to the creation of the ELIXIR Software Management Plan can be found in the respective [BioHackrxiv article](https://biohackrxiv.org/k8znb/)

> Alves, Renato, Dimitrios Bampalikis, Leyla Jael Castro, José M. Fernández, Jennifer Harrow, Mateusz Kuzak, Eva Martin, et al. 2021. “ELIXIR Software Management Plan for Life Sciences.” BioHackrXiv. October 25. doi:10.37044/osf.io/k8znb.


## Software Management Plan Expectations

Focus on the lifecycle but NOT the sustainability aspects of research software


## The ELIXIR Software Management Plan community

## SMP stakeholders

We identified two main stakeholders’ groups corresponding to users and adopters. In addition, we defined a group of distinguished personas that are out of the scope of the SMP’s stakeholders, specifically the (a) **software users** who might also be contributors (e.g. by submitting bugs), and (b) the **end-users** of the software, who have no involvement with the software development process.

For each group of identified stakeholders we answered two questions: (i) how the stakeholders would use the SMP and (ii) at which stage of the software development the stakeholders would need the SMP most.

### Group 1: Users / Benefiter / Enforcers

This group includes stakeholders that require access to the SMP for a given software, but are not responsible for filling it in.

**Funders** e.g ELIXIR, Wellcome Trust
**Policy Makers** e.g. European Commission (can use SMPs as a way of "enforcing" their recommendations and policies)
**Service providers** (e.g. Compute Platform, PaaS, IaaS, SaaS use an SMP in order to ensure compatibility to the infrastructure offered)
**Software manager** not necessarily contributing to the software - making sure principles are enforced
**Publishers** e.g. [F1000](https://f1000research.com/) should use an SMP in order to ensure software "quality" / availability?)


### Group 2: Adopters

This group includes stakeholders that are primarily responsible for filling a SMP for a given software.

**Developer/Researcher** the person writing the software needs to be aware of the basic principles to follow
**PI of a group** can use the SMP to ensure compliance with best practices)
**Organisation (Fundee)** Vested interest that in-house research output meets criteria and is sustainable - select appropriate SMP. This is the instance where an Institution is attempting to create a policy for internal use (ensure that any “badged” research software produced under it, aligns to the expectations of the selected SMP)

For more information, please see the respective [BioHackrxiv article](https://biohackrxiv.org/k8znb/)

> Alves, Renato, Dimitrios Bampalikis, Leyla Jael Castro, José M. Fernández, Jennifer Harrow, Mateusz Kuzak, Eva Martin, et al. 2021. “ELIXIR Software Management Plan for Life Sciences.” BioHackrXiv. October 25. doi:10.37044/osf.io/k8znb.


# What are the ELIXIR Software Management Plan Questions

ELIXIR SMP version 1.0.0 (date ??/??/??)

-> add list of questions

You can find these questions as ready-to-use templates in the links below:
- MD version
- Docx version
- PDF version
- Data Stewardship Wizard version
- RDMO version


# Which tools can be directly used with the ELIXIR SMP

The following tools have been tested and are ready to use:

1. ELIXIR Software Management Wizard: https://smw.ds-wizard.org/ 

2. RDMO (link?)

# Governance of the ELIXIR SMP

## How the ELIXIR SMP is maintained

The ELIXIR SMP is updated by incorporating the community feedback, which is done through an open editorial process (see maintenance below). You don’t need to be part of ELIXIR in order to provide your feedback and to contribute.

All questions listed in this page above are the latest version, including the templates provided. All old versions are available directly through the Github repository.


## Maintenance

### Maintainers group

- **Chair**: person with the ELIXIR Lead role (Eva)
- **Co-chair**: another person
- **Members**: -> to add our names and affiliations, not emails/contact details

### Editorial Process

The maintainers group meets online on a quarterly basis, with the details (date, time and connection details) announced through the mailing list at least 3 weeks in advance.

Before this call, all issues raised in the GitHub repository will be prioritised by the maintainers group with regards to impact and severity.

During this call, all issues will be discussed in order of priority, and based on the discussion and consensus by all TC participants, they will be tagged as “to be integrated”, “further discussion necessary”, or closed if assessed by the group as not applicable/suitable/relevant/duplicated/etc <polite way of saying “not useful/relevant”>.

After the first and third quarterly call of the year, all “to be integrated changes” to the ELIXIR SMP questions will be added to the questions, in order to create a new release/version of the ELIXIR SMP.


## How to contribute

Everyone is welcome to contribute to the discussion. You can participate in the following ways:
Open an issue in the GitHub repo, following the rules and guidelines listed.

In order to contribute to a GitHub issue, we expect all contributors to make use of the provided tags, and ensure (as much as feasible) that there are no other conflicting discussions.

Each tag corresponds to a different question.

Follow the CoC (copy contributions guidelines from somewhere)

Join the dedicated mailing list of the SMP group

RO Crate community -> open an issue with a specific message that they want to join the community

Shared calendar with the invites?


# About

## Team behind the definition of the ELIXIR SMP

Acknowledgements to everybody involved (i.e. everyone who has ever contributed to the ELIXIR SMP discussion over the past 3 years)

## Resources

- **BioHackarxiv article**: Alves, Renato, Dimitrios Bampalikis, Leyla Jael Castro, José M. Fernández, Jennifer Harrow, Mateusz Kuzak, Eva Martin, et al. 2021. “ELIXIR Software Management Plan for Life Sciences.” BioHackrXiv. October 25. doi:10.37044/osf.io/k8znb.
- **ELIXIR SMP Training lesson**: https://elixir-europe.github.io/elixir-smp-lesson/

