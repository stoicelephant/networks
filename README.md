# networks
here are the associated papers and website links with each of the projects - all of the networks were sourced from [sociopatterns](http://www.sociopatterns.org/)
---------------------------------------------------------------------------------------------------
Workplace - [Workplace Website](http://www.sociopatterns.org/datasets/contacts-in-a-workplace/), [Workplace Paper](https://www.cambridge.org/core/journals/network-science/article/abs/data-on-facetoface-contacts-in-an-office-building-suggest-a-lowcost-vaccination-strategy-based-on-community-linkers/18AB49AB4F2AEA33CE7501F06ADBC8E8)

Workplace II - [Workplace II Website](http://www.sociopatterns.org/datasets/test/), [Workplace II Paper]([http://www.sociopatterns.org/publications/can-co-location-be-used-as-a-proxy-for-face-to-face-contacts/](https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-018-0140-1))

Hospital - [Hospital Website](http://www.sociopatterns.org/datasets/hospital-ward-dynamic-contact-network/), [Hospital Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0073970)

High School - [High School Website](http://www.sociopatterns.org/datasets/high-school-contact-and-friendship-networks/), [High School Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0136497)

Primary School - [Primary School Website](http://www.sociopatterns.org/datasets/primary-school-temporal-network-data/), [Primary School Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0023176), [Primary School Paper 2](https://bmcinfectdis.biomedcentral.com/articles/10.1186/s12879-014-0695-9)

Science Gallery - [Science Gallery Website](http://www.sociopatterns.org/datasets/infectious-sociopatterns-dynamic-contact-networks/), [Science Gallery Paper](https://arxiv.org/pdf/1006.1260)

Conference - [Conference Website](http://www.sociopatterns.org/datasets/hypertext-2009-dynamic-contact-network/), [Conference Paper](https://arxiv.org/pdf/1006.1260)

## Data Description 
In both networks a The system was tuned so that whenever two individuals wearing the RFID tags were in face-to-face proximity(<1.5m) the probability to detect such a proximity event over an time interval of 20 seconds was larger than 99%. A contact is therefore symmetric by definition, and in case of contacts involving three or more individuals in the same 20-second interval, all the contact pairs were considered. After the contact is established, it is considered ongoing as long as the devices continue to exchange at least one packet for every subsequent 20 s interval. Conversely, a contact is considered broken if a 20-second interval elapses with no exchange of packets

Most of the data follows the general format node_1, node_2, Date_time. Where the time interval for which the contact was active is [ t – 20s, t ] (i.e for Date_time of July, 3rd 05:24:20, this represents the time interval from 05:24:00 - 05:24:20) 

## Overview

### Workplace :

The study took place in one of the two office buildings of the InVS, located in Saint
Maurice near Paris, France, and lasted two weeks in 2013. The building hosts three scientific
departments—the Direction Scientifique et de la Qualit´e (DISQ, Scientific Direction),
the D´epartement des Maladies Chroniques et des Traumatismes (DMCT, Department
of Chronic Diseases and Traumatisms) and the D´epartement Sant´e et Environnement
(DSE, Department of Health and Environment)—along with Human Resources
(SRH) and Logistics (SFLE). DSE and DMCT are the largest departments, with
more than 30 persons each, DISQ and SRH consist of around 15 persons, and
finally logistics consists of only 5 persons (Table 1). DISQ, DMCT, and SFLE share
the ground floor, while DSE and SRH are located on the first floor.
Two-thirds of the total staff agreed to participate to the data collection
![image](https://github.com/user-attachments/assets/843b4057-efd4-4419-84db-8a3b3907247e)

Additional Notes: 

In particular, we find broad distributions with an approximate power-law shape for
weights, contact, and inter-contact times, which are typical of the heterogeneous
behavior often found in human activities (Barabasi, 2005).


### Workplace II:

The study took place in one of the two office buildings of the InVS, located in Saint
Maurice near Paris, France, and lasted two weeks in 2015. There were ? particpants with ? rfid tags giving a coverage of ? 

Additional Notes:

Consider using the Workplace I dataset instead 

### Hospital:

Data were collected in a short stay geriatric unit (19 beds) of a university hospital of almost 1000 beds [3] in Lyon, France, from Monday, December 6, 2010 at 1∶00 pm to Friday, December 10, 2010 at 2∶00 pm. During that time, 50 professional staff worked in the unit and 31 patients were admitted. We collected data on the contacts between 46 staff members (92% participation rate) and 29 patients (94% participation rate). The participating staff members were 27 nurses or nurses’ aides, 11 medical doctors and 8 administrative staff.

Additional Notes: 

Each day 2 teams of 2 nurses and 3 nurses’ aides worked in the ward: one of the teams was present from 7∶00 am to 1∶30 pm and the other from 1∶30 pm to 8∶00 pm. An additional nurse and an additional nurse’ aid were moreover present from 9∶00 am to 5∶00 pm. Two nurses were present during the nights from 8∶00 pm to 7∶00 am. In addition, a physiotherapist and a nutritionist were present each day at various points in time, with no fixed schedule, and a social counselor and a physical therapist visited on demand (in our analysis they are considered as nurses). Two physicians and 2 interns were present from 8∶00 am to 17∶00 pm each day. Visits were allowed from 12∶00 am to 8∶00 pm but visitors were not included in the study.

### High School: 

Here we present and analyze data sets corresponding to these various types of interactions and collected through concurrent data collection methods among more than 300 high school students during one week in December 2013. The data collection concerned high school students of specific classes called “classes préparatoires” in Lycée Thiers, Marseilles, France.They study in a high school environment but are de facto mostly separated from the “regular” high school students: their classes are located in a different part of the high school building and they typically take their lunches separately. They constitute thus an almost closed population with few contacts with the outside world, at least during workdays.we gathered contact data of the 327 participating students (out of 379 in the 9 classes, i.e., a 86.3% participation rate) during the week of Dec. 2-6, 2013.

Additional Notes:

Paper had corresponding Facebook Network for the Nodes 

### Primary School: 

The study took place in a primary school in Lyon, France during two days in October 2009. The age of the students (elementary cycle, composed of 5 grades) ranges between 6 and 12 years. In this school, each of the 5 grades is divided in two classes, for a total of 10 classes. Each class has an assigned room and an assigned teacher. The smallest class has 22 children and the largest 26, for a total of 241 children and 10 teachers. 232 children and all teachers participated in the data collection. The school day runs from 8.30am to 4.30pm, with a lunch break from 12pm to 2pm, and two breaks of 20–25 min around 10.30am and 3.30pm. Lunches are served in a common canteen, and a shared playground is located outside the main building. As the playground and the canteen do not have enough capacity to host all the students at the same time, only two or three classes have breaks at the same time, and lunches are taken in two consecutive turns.

Data on face-to-face interactions between 232 children (96% coverage) and 10 teachers (100% coverage) across 10 classes were collected over two days (Thursday, October 1st 2009 and Friday, October 2nd 2009,  Data were collected from 8.45am to 5.20pm on the first day, and from 8.30am to 5.05pm on the second day. Contacts were not recorded outside of these time intervals

Additional Notes:

No information on contacts taking place outside the school or during sports activities was gathered

### Science Gallery:

the event was the INFECTIOUS exhibition held at the Science Gallery in Dublin, Ireland, from April 17th to July 17th, 2009

Additional Notes: 

Network may not be appropriate since the contacts are different individuals everyday (fixed location not fixed participants) 

### Conference:

event was the ACM Hypertext 2009 conference [34] hosted by the Institute for Scientific Interchange Foundation
in Turin, Italy, from June 29th to July 1st, 2009.

Additional Notes: 

Network may not be appropriate since the contacts are di9fferent individuals everyday (fixed location not fixed participants) 
