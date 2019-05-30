# Network-of-ontologies
<a href="http://postdata-prototype.linhd.uned.es/ontology.php" target="new">Network of ontologies for European Poetry</a>  covers all aspects concerning poetic works, their manifestations, their transmission and the classes and properties necessary for the representation of information coming from structural, prosodic and literary analysis and related aspects such as musical characteristics and elements present in manifestations such as illustrations.
	 	<p>The process of constructing the network is described in <a href="http://postdata-prototype.linhd.uned.es/ontology.php" target="new">this link</a> and has resulted in the following ontologies:</p>
	
		 
	  
<h4> <a href="http://postdata.linhd.uned.es/ontology/POSTDATA-core/">1. postdata-core ontology</a></h4>
(https://github.com/linhd-postdata/core-ontology)
	<p>This ontology covers with aspects related to poetic works and their manifestations.</p>
<P>The classes PoeticWork, Redaction and Ensemble have been defined for this purpose.</P>
<P>Since it is the core or central ontology of the network, classes that are not typical of one of the domains related to poetry but that represent a transversal knowledge have also been incorporated. These classes complete the relevant information not only for the classes of the core ontology but also for other ontologies of a more specific domain. </P>
<P>The following entities have therefore been identified: 
<ul><li>Person and Organisation, to model the agents that intervene in the poetic work with different roles.</li>
<li>CreatorRole and Role that model the authorship or creation of the works and elements of manifestation and transmission and other roles as editor, for example.</li>
<li>Place and Event, to represent places of origin and mentioned events.</li></ul></P>
<p>The core ontology, would be imported by the rest of ontologies of the network, for this reason besides containing the mentioned classes, it also provides a set of common properties that have the same semantics in all the classes in which they are defined. In this way it is possible to express semantics in an unambiguous way for properties that from this point of view represent conceptually the same thing.  </p> 

<h4><a href="http://postdata.linhd.uned.es/ontology/POSTDATA-dates/">2. postdata-dates ontology</a></h4>
<p>From the properties of data associated with classes, which are related to the dating of the work, its manifestations and its transmission, some characteristics have been identified, especially in the form of expression of the date, which are commonly used in the domain in question or in literary domains in general. In this domain, the difficulty of dating works according to established formats must be taken into consideration. Many times the dates cannot be determined with the required accuracy and many times they are compromised by the lack of accuracy of the date, which also requires additional elements of information to comment on issues of dating. 
From the foregoing, it has been considered appropriate to propose the creation of a small ontology of dates in which the forms of representation of dates in the context in which work is being carried out and the possibility of incorporating additional information.  </p>
	 <h4><a href="#">3. postdata-transmission ontology</a>(in process)</h4>
	 <p>In this module the classes and properties referring to the transmission of the works are modelled. The classes of this module are PrimarySource, BibliograhicSource, Witness, WitnessCollection, Repository, Facsimile, Reading, Apparatus, Location. </p>
			 <h4> <a href="#">4. postdata-literaryAnalysis ontology</a>(in process)</h4>
<p>In this module, the classes and properties referring to the classes that are necessary to obtain information from literary analysis are modeled.  The classes in this module are Acrostic, Intertextuality, RhetoricalDevice. </p>
			 <h4> <a href="#">5. postdata-structuralElements ontology</a>(in process)</h4>
<p>In this module, the classes and properties referring to the classes and properties that have to do with the textual structuring of the manifestations of the works are modelled. 
The classes that compose it are: Syllable, Line, Stanza, Word and Punctuation, these last two belong to a LexicalUnit hierarchy.  </p>

<h4> <a href="#">6. postdata-prosodicElements ontology</a>(in process)</h4>
			 <p>In this module, the classes and properties that model the information necessary for the prosodic analysis of a poetic text are modeled. As in other modules, a hierarchy of classes has been defined that models the patterns of different levels and that are oriented to define the recurrence of the pattern followed by the stanzas, the lines and the poetic work itself. 
The classes that form this module are LinePattern, StanzaPattern, Work Pattern, Métrical Encoding, Symbol, RhymeMatch. </p>
<h4> <a href="#">7. postdata-music</a>(in process)</h4>
<p>The POSTDATA ontology network also takes into account the characteristic presented in many poetic works, which is the presence of musical representations in the manuscripts, with their codification and the musical manifestations of many of the works. 
In this ontology, we have not sought a detailed representation of the musical characteristics but those that can enrich the text and play an important role as a complement. The classes are: Melody, MusicalNotation, Performance </p>
	<h4><a href="#">8. postdata-additionalFeatures ontology</a>(in process)</h4>
	<p>In the manifestations of poetic works, elements that increase the expressiveness of the works appear regularly. The aim of this ontology is to cover these aspects. The classes identified in the model are : Paratext, Illustration and Scene. </p>
	</div>
