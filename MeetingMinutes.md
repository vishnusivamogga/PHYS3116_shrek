# Meeting Minutes #

## Meeting 1 - 18/09/2025, 9.50 pm (Week 1)
Note: This was completed in week 1 on a google document and committed once we had the github working

**Meeting duration**: 25 minutes

**Agenda:**
1. Read the assessment briefing
2. Distribute the workload
3. Set deadline 
4. Install and get used to github and VS code and create a notebook for the code

**Attendance:** Vishnu and Sarvpreet (third teammate missing)

**Workload distribution and plan to tackle the assessment**

Vishnu will take the Harris catalogues and make a list of accretion candidates solely based on the dynamical information in the catalogue (and beyond). 
Sarv will make a list of accretion candidates solely based on the age-metallicity distribution.
We will compare the two lists and see what is missing and maybe combine the methods for a comprehensive analysis of which clusters are accreted and which are in situ. 

**Discussions and Decisions**

Apart from the workload plan, we have decided on a thursday evening weekly meeting on top of the lecture meets so we can get ahead and discuss it more thoroughly as the lecture breaks are short. 

**Action items for next thursday’s meeting**

Sketch out the details of the problem - what are the characteristic features of GC’s to look for, what are the mechanics of the accretion, what signs does accretion leave, the contents of the CSV data [BOTH SAV AND VISHNU]

Begin coding your section as sketched out in the workload distribution. 

## Meeting 2 - Thursday week 2 in the break (and after the tutorial)

**Meeting duration:** 30 minutes

**Attendance:** Vishnu and Sarvpreet (third team mate missing)

**Agenda:** 
1. Sort out an issue with understanding the merge conflict
2. Analyse Vishnu's dynamical plots and consolidate next steps and see if the plan needs a change
3. Lay out how Sarvpreet should do his plots and the next steps. 

**Discussions and Decisions**

Vishnu generated plots of the clusters with energy and angular momentum, and made a cut to make a list of accretion candidates. The initial straight line cut was too strict - the idea we had was to start with quite a generous selection of candidates and narrow it down by looking at it spatially. He then did a parabolic cut which worked better, and looked at it spatially which also worked quite well. 

After Energy and Angular momentum was plotted, an initial cut by figuring that the retrograde GCs and higher energies are more likely to be accreted GCs. This cut revealed around 42 GCs excluding some clear outliers which is our initial estimate for the accreted GCs

Sarv has been wrestling with the github mostly - he has however imported and inspected the files and is aiming to get it done by tonight so we can discuss and fine tune the method better.

Both of us have spent a while resolving a merge conflict. 


### Action items
1. For Sarv: make an age metallicity plot and try and make a cut to see if you can make your own list of candidates. Compare this with Vishnu's list and inspect for discrepencies. 

2. For Vishnu. See if you can optimise how you selected it or figure out a way to further emphasise why the current selection is valid. Once Sarv has the age metallicity candidates list, maybe combine the two.

3. For both: Read further on existing literature and understand the signatures of an accreted GC vs a non-accreted one. 

4. To avoid merge conflicts in the future, ensure you use the procedure: PULL, then EDIT, then STAGE, then COMMIT, then PUSH. 


## Meeting 3: 28/09/2025 9pm - sunday evening meeting

**Meeting Duration:** 

1 hour and 15 minutes

**Meeting attendants:** Sarvrpreet, Vishnu, William

**Agenda**

1. Explain the assignment to William and our progress on it so far
2. Help William set up his github repo and teach him pushing ettiquette
3. Assign William a part of the assignment and set deadlines
4. Discuss the applications of the HB column of the Vandenburg table for making the age-metallicity selection list even better.

**Discussions and Decisions**

William is to work on the big question of what the list of accretors imply for the formation of the milky way. 
1. Have these globular clusters existed before the Milky Way? If so, how long?
2. Why are there in-situ vs accreted clusters? 
3. What are some tests we could do to verify our theory of milky way formation in light of our accretors list? 

William's coding component will involve actually implementing some of these tests. 

Another discussion item was the possibility of using the vandenberg HB column, plotting it by metallicity and colour coding by age. By doing this, we could filter out between older, low metallicity, more evolved clusters to younger, low metallicity less evolved stars.

**Action Items**

1. William should read some papers and figure out exactly what kind of tests we should implement.
2. Sarv should attempt to use the HB column and make a list of accretion candidates the same way Vishnu did
3. Vishnu should research the implications of spin up and spin down and see if he can refine the accretion candidates he has even more with that. 






