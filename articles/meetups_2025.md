# HPC RSE SIG Meet-ups 2025

## Online Meet-up May 19

This online meet-up was the first meet-up of the community after officially going through the process of becoming a Special Interest Group under the Society of Research Software Engineering. 

We had a range of interesting talks from the HPC RSE community:

### Scaling the Stars: Optimizing MPI communication on GPUs in the PROMPI stellar dynamics code; Miren Radia, Research Computing Services, University of Cambridge
[presentation](https://drive.google.com/file/d/1XJG-h6JUjAa7GXg2J8KbZm_7p2HRV4Jm/view?usp=drive_link)

### Custom Acceleration Frameworks: the good, the bad, and the ugly; Ilektra Chritidi, Mashy Green, UCL
[presentation](https://docs.google.com/presentation/d/11Gf0vOFh4GKP9rFxEjzTe9TM08WPHF4E/edit?usp=drive_link&ouid=117268427484378159786&rtpof=true&sd=true)
In this talk, Mashy green talked about their experiences working with custom abstractions on accelerator offloading.
As a HPC RSE, it is good to be aware of the pros and cons of different software options for offloading, from native languages like CUDA and HIP to third party libraries such as Kokkos and Raja.
Developing and maintaing your own custom framework within a codebase is a major effort but it can pay off if you really need to fine tune the performance and abstraction balance for a specific codebase.

### FRIDGE: A shared responsibility model for deploying Trusted Research Environments on High Performance Compute systems; Martin O’Reilly, The Alan Turing Institute
[presentation](https://drive.google.com/file/d/1Vf8W8923u_0tHhUE6gqzFuGgWnLgSyS8/view?usp=drive_link)
### Connecting the DRI community through CAKE; Nick Brown, EPCC, University of Edinburgh

These were followed by a group discussion on what the HPC RSE community would like to see from the SIG going forward.

## In-person Meet-up at Durham HPC Days, June 5

At the Durham HPC Days, which traditionally happen in Durham in the week preceeding ISC, we had a session blocked to meet-up in person.
Although a lot of HPC RSEs were torn between this session and the session on Benchmarking, which ran in parallel, we still had a good group of people in the room.
Some of them were new to the HPC RSE SIG and heard for the first time about what we do and how we are related to the RSE Society and the HPC SIG.

After a short introduction, we ran world-cafe-style discussion around the topics of career and training, technology and software, and community.
For each of these topics we discussed positive and negative aspects, as well as ideas we had.

### Technology and Software

- Positive: Some random techy bits: There is great local support for Tier 2, new Spack version is coming out soon.
Many of us are excited about the current situation with lots of change, and new problems to tackle.
There are impressive technologies out there, and the combination of HPC and AI has huge opportunities.
AI can also be useful for coding (if you check and correct/adapt)
- Negative: Again, Tier 2s: support and funding is disappearing.
:( Procurement is slow, especially for GPUs. There is a lot of badly written code out there, and people start to rely too much on LLMs.
There is a fear that AI tools will change our jobs and careers, and not everyone likes that (or will be better off).
And generally, the amount of "stuff" (AI, cloud, HPC,...) out there can be overwhelming.
- Ideas:
  - Literacy for users on sustainable use of software.
  - Use synergy between HPC and AI, foster collaboration.
Not everyone needs to do AI - but it also should not be a case of "us vs. them".
We should join teams, where appropriate, and become a "we".
  - There are mixed experiences with using AI for coding - good for explaining code.
  - Improve interpretability for compiled languages.

### Training and Careers
- Positive: Places like the MetOffice have proper career progression without the requirement to publish and with a proper skills framework, and even level 6 apprenticeships - this would make a great case study.
The RSE movement has been quite successful over the past >10 years.
The relationship with IT can work well, and many RSE teams at universities do "sales pitches" to research departments, and/or use training to get a "foot in the door".
People also get writting into grants (or even become Co-I), and mobility between universities/groups is reasonably good.
- Negative: The university model with its academic tenure track and values does not fit well for most RSEs - what would be the "professor level" for an RSE?
There is still a lot of push-back when RSEs want to lead on grants (often they are not included in the grant writing process), and at many universities, RSEs are pushed into professional services - which, again, is often not a good fit. 
For career progression, in most places, you have to apply for a new position.
- Ideas:
  - Show the benefits of a close link between RSEs and scientists.
  - Co-locate expertise - not RSEs and equipment.
  - Embed RSEs into research groups, while maintaining central "best practice" links and links to IT.
  - Formalise IT/Research straddle/leadership model.
  - Flexible roles which don't require grants and publication. => more opportunities
  - Advertise the [UK Institute for Technical Skills and Strategy (ITSS)](https://itss.org.uk/) - people don't know about it!

### Community

- Positive: Slack and other online platforms are great for connecting people, and have a low barrier (not as scary as in-person), while conference and in-person events are great for networking. 
There are amazing skills in the community, and especially the RSE community is organised really well.
- Negative: There are still local groups which are not well connected to the wider RSE community.
It can often be difficult to find the time alongside the day job.
Online communication platforms can be overwhelming, and not all info is trickling down to the right people.
There is still a lack of visibility of RSEs and their specialisms outside their community and traditional science, and knowledge exchange beyond Slack is needed.
Also, outcomes of RSE projects and capabilities of RSEs need to be advertised better.
- Ideas: 
  - More social online networking outside of conferences would be useful for those who are socially insecure. 
  - Active outreach to non-traditional communities.
  - Accepting RSEs as PIs - cultural change.
  - Breaking stereotypes.
  - Sales training/outreach skills. => promote what RSE means, but also outcomes and work done


## HPC RSE Birds-of-a-Feather RSECon25

[HPCRSE@RSECon25: 4th annual meeting of the HPC RSE community](https://virtual.oxfordabstracts.com/event/75166/submission/66)

### Evgenij Belikov: [Monitoring hardware performance counters on ARCHER2 using LIKWID](https://drive.google.com/file/d/1ovhbUe8vni2c5R5TMSepVapRBh3ZVUiN/view?usp=drive_link)

This presentation covered using the open source performance counter tool [LIKWID](https://hpc.fau.de/research/tools/likwid/) on ARCHER2.
The speaker explained how to use this tool for ensuring you use HPC resources effectively, without the need to recompile or edit your code.
The examples included `likwid-pin`, `likwid-perfctr` and the main workhorse on ARCHER2 `likwid-mpirun`.
Custom features were added for it to run on ARCHER2 and was demonstrated with example job scripts and outputs.
At the end there were a few questions asked where the speaker provided more information on additional resources (docs, webinar and training courses) and clarified that likwid does provide energy measurements.

### Mosè Giordano: [Accelerating scientific code with Reactant.jl](https://docs.google.com/presentation/d/1bjjBIQXc1OSr0Lvs6cYAlIlvR4sC24PbrXM8LdgEZIE/edit?usp=sharing)

The speaker presented a large collaborative project between academia and industry developing the Julia package [Reactant.jl](https://enzymead.github.io/Reactant.jl/stable/).
It was explained this project was inspired by [Oceanianigans.jl](https://clima.github.io/OceananigansDocumentation/stable/) and is used a test case for this project.
The speaker presented current issues faced with a kernel compiled with just LLVM mainly due to how low level it is.
The addition of raising underlying structures to MLIR can preserve host and device code all together which can allow parallel specific optimisations.
Reactant.jl can be seen as a frontend to MLIR and when this was used with Oceaniangans.jl no substantial changes were needed.
The presenter showed that Reactant is an optimising framework written in Julia which preserved high level structures and the acceleration effects were showcased on TPUs.
In the Q & A the speaker explained more on the speedup and how this will integrate with other Julia packages.

### Technical/Exascale Panel

The panel brought back up both speakers and also had the addition of Alex Lyttle a Senior RSE from the University of Birmingham.
The first question related to integrating performance test into a CI pipeline.
The panel as well as members of the audience provided key input based upon their experiences.
Ideas ranging from using [Reframe](https://github.com/reframe-hpc/reframe) and successes with [Jacamar](https://gitlab.com/ecp-ci/jacamar-ci).
Moving away from GitHub to have a locally hosted GitLab was also discussed.
A question about dedicated hardware was posed with accelerators like FPGAs used as an example.
This was mainly around their custom workloads and its use by CERN for specific timing constraints.
The last question was about the growing diversity of architectures and the current state of performance portability.
Mose Giordano related it back to presented work and MLIR.
Other packages like Kokkos and the device agnostic nature of higher level python packages.

### Future of UK HPC Service Panel

This panel had:
- Chris Edsall (University of Cambridge, CSD3 and DAWN)
- Matt Williams (University of Bristol, Isamabard AI)
- Andy Turner (EPCC, ARCHER2, involved with DIRAC)
- Simon Burbidge (DIRAC)

Each of the panel members introduced themselves, their institution and the HPC facilities they work with.
The first discussion topic was the 2026 grant roadmap and the associated computing challenges.
The panel spoke about changes in the governments funding approach moving towards more national compute with more centres of excellence to provided added diversity to UK compute resources.
A need for skilled people with knowledge of AI and AI software was also mentioned.
This discussion led to a further question on what strategies the UK should adopt where examples from around the world were discussed, most notably how the French government provides funding for GPUs.
That led to a greater discussion on GPU provisioning and the energy concerns and how the current strategy works well for the government due to the expertise of everyone getting the most results from a given hardware.
This allowed further questions and discussion on future hardware procurement, HPC sustainability, energy usage of current and older systems as well as increasing the lifecycle of hardware.
This panel presented an interesting discussion with a lot of questions and the audience wanting a longer session to continue to hear from the panel.

### Jost Migenda: [Python Profiling & Optimisation & Other Activities of the RPC SIG](https://drive.google.com/file/d/1IsXb_Pptls1W7PM1uGeHhC7HPjiGVd4j/view?usp=sharing)

This presentation is an invitation for further collaboration between the reasonable performance computing [RPC SIG](https://sig-rpc.github.io/) and the HPC RSE SIG.
The issue of researchers not considering performance and efficiency was stated and that there is a lot of low-hanging fruit to optimise and profile their code.
After outlining the situation a demonstration of the carpentries styled course on profiling and optimising python code was shown (https://carpentries-incubator.github.io/pando-python/). 
The presentation ended with a call for collaboration on both the course material and the RPC SIG.


### Sara Villa: [Open communities as an essential part of upskilling and training development](https://docs.google.com/presentation/d/1c55gGoWgxzE2TxbsATilY_RSlW8P8FufPMuIcVlw8Ec/edit?usp=sharing)

The speaker outlined both open communities and the open seeds training program.
They explained their experience and work done in both the Turing way and OLS.
Open communities were described as making teaching efforts sustainable following the method of "Training the trainers".
Upcoming events Open leadership training and ally skills workshop were advertised during this presentation.
After outlining the communities and events the presenter states that this is an opportunity for the HPC RSE SIG community to work and contribute to them.

### Community and Training Panel

The panel brought back both speakers as well as Mashy Green (UCL), Janetta Steyn (Newcastle) and an audience member agreed to join our open invite.
The panel provided their views and experiences on training senior academics.
They outlined the difficulties they have had with them being resistant to change, time constraints in training them.
How to get academic institutions to fund training was asked and discussed amongst the panel.
Sustainability and energy consumption were a common theme throughout the event and was also asked in this session, particularly as training others to be conscious of energy consumed both in AI tools and in running code.
Further discussion of embodied emissions, run time estimates for energy use, linking back to the reasonable compute sig and how to train users to understand how much compute is necessary to solve a problem.
The final question asked about specialised HPC hardware and training users to use it.
The panel spoke about the benefits of higher efficiency for certain workloads.
Also, how compiler level portability helps test more hardware as well as how DiRAC GPU feasibility studies found that applications can drive procurement choices.
