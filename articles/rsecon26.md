# HPC RSE SIG annual conference RSECon26

## Lightning talks [presentation](https://docs.google.com/presentation/d/1YAhkJ2zuFuXiRMLV9gB6xpT5S13wY5x8B40JmLiGAUc/edit?usp=sharing) 

### CSC-IT Center for Science, Finland - Samantha Wittke

### Zenith: a new system for HPC and AI - Miren Radia

### The Bristol Centre for Supercomputing - Paul Wright, Anna Price and David John

### EuroHPC access for UK researchers: Opportunitues beyond local HPC - Ashutosh Shankarro Londhe

### bwRSE4HPC - Glen Hunter

## Community discussion

### How to avoid reinventing the wheel again and again in HPC training

- Agreed that sometimes slight changes will need to be made to the training material
   - Differences in HPC systems
   - Need resources to be easy to edit for different presenters
- Make everyone aware of all the different trainig resources:
   - Direct - [dRTP skills framework](https://directframework.com/)
   - Evita - are trying to provide a unified training infrastructure across [EuroHPC systems](https://www.evitahpc.eu/) and a [hpc portal](https://hpc-portal.eu/)
   - [SHAREing training](https://shareing-dri.github.io/training/)
- Make successful trainining resources accessible like [Carpentries](https://carpentries.org/)
- Funding
   - For those who have the material to travel and deliver the material
   - For a central location for those to travel to

### How to encourage collaboration and knowledge exchange between international HPC centers

- EuroHPC and EuroCC efforts are aimed at users across nations for whom the site caters
- Time from individuals may be one of the biggest limiters for such collaborations
- RSEs, in some groups, are expected to spend 10% of their time or so for such collaborative efforts
- Mandating collaboration amongst 2-3 institutions in contributions can be part of a workshop proposal at a conference
- A regular meeting of a working group working on such an initiative is the best way to have steady progress
- Keeping trainings open to wider audiences is always helpful
- Set up a GitHub repo, encourage PRs from RSEs who want to submit an idea -> can be a good idea to invite participation 
- User group meetings that bring experts (RSEs, platforms, etc.) together work well
- Coffee breaks, office hours, can bring users and experts together (LUMI, OLCF are good examples)

### Environmental impact of HPC and AI discussion:

- General chat about how our diff hpcs work
- Improivng hpc training to include a focus on job efficienccey
- Stricter limits to get onto ernegery intensive hardware
- Discussion about underclocking or even powering off nodes
   - Potential trade offs with embedded carbon
- Power density is going up, so to maintint he same capacity then power usage wil go through the roof
- Change scheudling algorithms to be tied to power generation, or have differnet projects have differnt weights based on what is being researched
- Lots of good ideas but limnited RIE straff to implement this
- Energy mix, should hpc sites have mandatory on site renewables, should they be located near green power eg scotland or york have a machine aborad next to hydro
   - Could we make researchers power the hpc on stationary bikes

### Does the current push towards “Sovereign Compute” in the UK mean we are moving away from globalisation and collaboration?

- Not necessary for there to be tension between sovereignty and collaboration
- Adoption of open standards can actually benefit collaboration
- Moving away from monopolised providers can distribute resources and risk more fairly
- Only real risk is with competing for hardware/resources, which could reinforce global inequalities
- Great potential in federation, improving privacy and research and control of resources by communities
- Distribution of compute is better for security and minimising risk
- Can have more compute in countries with greener energy?

### What makes good docs?

- We're technical people so maybe we're not the best judges for this
- What's a good baseline?
   - Can we assume they know how to SSH?
- Searchable
- Could have an AI chatbot that can search through the docs and answer queries like vLLM
- Some users won't even go through a terminal i.e. Open OnDemand (web browser) only
   - Maybe a different path through docs for these kinds of users
- Policies as well as how to do something
- Videos can be helpful for new users and those unfamiliar with HPC.
- Web Analytics to determine page usage
- Software stack information is often accessed regularly
   - How to load the modules
