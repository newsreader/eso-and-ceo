README: Framenet lexical unit to Princeton Wordnet synset mappings and to the ESO ontology

Date: June 10th 2015
Author: Roxane Segers (r.h.segers@vu.nl)

The file "UPDATED_mappings framenet and wordnet.csv" contains the ±90 frames that were used in the Event and Situation Ontology.
All lexical units of these frames have been mapped manually to Princeton Wordnet 3.0, using the Wordnet and SUMO browsing tool at http://www.adampease.org/OP/. The mapping was performed as not domain-specific to ensure reuse across domains.


Please note that the pre-, post and during situations as defined in ESO should (more or less) hold for the mapped synset. Due to the organization of Wordnet, this will obviously not always be the case for the hyponyms of a mapped synset. (Selectional restrictions and complementation may vary)


Note that some lexical units have mappings to multiple synsets. Also, a single synset ID can be mapped to multiple lexical units. Furthermore, a synset synonym can be mapped to multiple frames. In the last case, these frames are closely related or overlapping (Motion, Cause_Motion)

All the lexical roles from the frame Leadership (king, duke, etc) have not been mapped.


File structure:

**COLUMN A: the ESO class name. 
Please note: in some cases an ESO class is followed by '/NOT'. This means that the pre and post situations from ESO do not hold for this LU (the LU expresses a negation). See for instance: 'BeingInAPersonalrelationship/NOT  Personal_relationship  widow'.
Please note: in few cases, an asterisk replaces the ESO class name. In these cases, the FN LU basically does not make sense (e.g. the LU 'independence' pertaining to Change_of_leadership) or the LU expresses a concept that cannot be related to an existing ESO class (e.g. 'fluctuate' from the frame Change_of_position_on_a_scale).

**COLUMN B: FrameNet frame. 
The default here is that there is a close match between the ESO class and the Framenet Frame. Otherwise, there is 'bm:' preceding the frame name, meaning that there is a broad match from the ESO class to the Framenet Frame.

**COLUMN C: Framenet LU
In few cases, an asterisk precedes the LU. In these cases, the asterisk marks a role: *assassin, *shoplifter. 

**COLUMN D,E,F, etc: synset IDs.



