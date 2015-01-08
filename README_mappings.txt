README: Framenet lexical unit to Princeton Wordnet synset mappings

Date: January 6th 2015
Author: Roxane Segers (r.h.segers@vu.nl)

The file "Mapping framenet and wordnet.xlsx" contains the ±90 frames that were used in the Event and Situation Ontology.
All lexical units of these frames have been mapped manually to Princeton Wordnet 3.0, using the Wordnet and SUMO browsing tool at http://www.adampease.org/OP/. The mapping was performed as not domain-specific to ensure reuse across domains.

Frames:
Amalgamation		Cause_change_of_position_on_a_scale	Come_togetherArriving		Cause_expansion				Commerce_buyAssemble		Cause_harm				Commerce_payAttack			Cause_motion				Commerce_sellBecoming_separated	Cause_proliferation_in_number		Commercial_transactionBeing_employed		Cause_to _fragment			CothemeBeing_located		Cause_to_amalgamate			CreatingBeing_operational	Change_of_leadership			DamagingBorrowing		Change_of_quantity_of_possession	DeliveryBringing		Change_position_on_a_scale		DepartingBuilding		Collaboration				Destroying

Dispersal		Get_a_job				LendingEmploying		Getting					Manipulate_into_shapeEscaping		Giving					ManufacturingExecution		Hiring					MotionExistence		Importing				Operate_vehicleExpansion		Installing				Personal_relationshipExperience_bodily_harm	Intentional_traversing			PlacingExporting		Intentionally_act			PossessionFiring			Intentionally_create			PresenceFleeing			Killing					Proliferating_in_numberForming_relationships	Leadership				QuittingQuitting_a_place	Sending					TraversingReceiving		Separating				Use_vehicleRemoving		Setting_out				Vehicle_departureRender_nonfunctional	Social_event				Vehicle_landingRenting			State					WorkingRenting_out		SupplyReplacing		Take_place_ofReshaping		TakingResidence		Temporary_stayRide_vehicle		TheftSelf_motion		Travel

Current contents:
-1564 lexical units from FN are mapped to PWN 3.0.
-1872 mappings to synsets:  1393 verbs, 412 nouns, 27 adjectives and 3 adverbs
-269 lexical units have no mapping to PWN: 1) the LU does not exist in Wordnet, 2) the sense was missing in Wordnet 3) the mapping was too problematic.

Note that some lexical units have mappings to multiple synsets. Also, a single synset ID can be mapped to multiple lexical units. Furthermore, a synset synonym can be mapped to multiple frames. In the last case, these frames are closely related or overlapping (Motion, Cause_Motion)

Lexical units from Framenet that express a role are marked with an asterisk, e.g:
*assassin
*snatcher
*shoplifter

All the lexical roles from the frame Leadership (king, duke, etc) have not been mapped.

///////////////////////////////////////////////////////////////////////////

Some ESO specific remarks:

-The NOT notion: in some cases a lexical unit has an additional NOT annotation that expresses that the pre and post situations of a class in ESO should be understood as negated in the case of this lexical unit.

Being_operational	broken.a	300680156	NOT
Possession		want.v		202632567	NOT

-Please note that the pre-, post and during situations as defined in ESO should (more or less) hold for the mapped synset. Due to the organization of Wordnet, this will obviously not always be the case for the hyponyms of a mapped synset. (Selectional restrictions and complementation may vary)

