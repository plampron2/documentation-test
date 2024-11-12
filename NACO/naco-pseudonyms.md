# FAQ – LC/PCC practice for creating NARs for persons who use pseudonyms.

**Background note:** The following practices for creating and relating names for persons who
use alternate identities are based on a tradition that evolved from the implementation of AACR 2
at the Library of Congress and was subsequently passed on to participants of the NACO
Program of the PCC. Staff at the Policy and Standard’s Division working with members of the
PCC standards and training committees are working to find a new mechanism for efficiently
creating and relating pseudonyms that will facilitate applying new elements that better identify
and relate the names in the context of linked data to newly created authorized access points as
well as to existing NARs. Suggestions, comments, etc. may be sent to **policy@loc.gov**

```
Q1. How many NARs are needed for persons who use pseudonyms?
```
```
A1. When considering how many NARs to create for a person with alternate identities
the LC/PCC cataloger should first consider the following six situations.
```
A1.1. The person uses one pseudonym and never uses the real name.
A1.2. The person uses the real name and uses only one pseudonym.
A1.3. The person uses more than one pseudonym and may or may not use the
real name.
A1.4. The pseudonym represents a joint collaboration by two or more persons
and the catalog does not contain items by those persons under their real name.
A1.5. The joint pseudonym represents a joint collaboration by two or more
persons each of who also use their real name and there are items in the catalog
under the real names.
A1.6. The pseudonym is used by several persons working independently of each
other.
Each situation is discussed below.

```
A1.1. The person uses one pseudonym and never uses the real name (RDA
9.2.2.8 exception; RDA 9.2.3.4).
```
```
Make only one NAR. Use the pseudonym as the 100 (Heading—personal name) and
add the un-used real name as a variant name in a 400 field (see reference) in the NAR.
See Bookmark Example 1. 1 Do not use Appendix K terms in the 400 field.
```
```
A1.2. The person uses the real name and one pseudonym (RDA 9.2.2.8)
```
```
Two NARs are created with simple see-also references (500 field) linking the two names.
LC/PCC catalogers may optionally use the relationship designators from Appendix K2.
to link the names. See Bookmark Example 1.
```

**A1.3. The person uses more than one pseudonym and may or may not use
the real name (RDA 9.2.2.8).**

NARs are created for all the names including the unused real name if known. When
more than two NARs are created one name is selected as the “basic” heading. The basic
heading technique simplifies the cross reference structure and provides a name for use
when the person is the subject of biographical or critical works. [See **Bookmark Q2** in
this FAQ for instructions on how to choose the basic heading and what MARC 21 fields
and subfields should be used] See Subject Headings Manual H430 for assigning subject
access points.

**Text in 663 field note of the basic heading.** In the NAR chosen as the basic
heading for the person provide a 663 note in subfield $a with the sample text
provided below. The text may be adjusted to fit the situation:

```
For works of this author written under other names, search also under: $b
[established form of name] $b [established form of name]
```
Precede each name in the 663 note with a subfield $b.

**Text in 663 note of related names.** In each of the related authority records created
for the person, provide a 663 note with the sample text provided below. The text may
be adjusted to fit the situation:

```
Works by this author are identified by the name used in the item.
For a listing of other names used by this author, search also under: $b
[established form of the name chosen as the basic heading]
```
**See Bookmark Example set 1.3.**

**A1.4. The pseudonym represents a joint collaboration by two or more
persons and the catalog does not contain items by those persons under their
real name. (RDA 9.2.2.6, Exception)**

One NAR for the joint pseudonym is created. The un-used names associated with the
pseudonym are provided in a 400 field (see reference) on the joint pseudonym NAR.
Apply this also in the case where one or more persons write under their real name and
the other or others do not. **See Bookmark Example 1.**


**A1.5. The pseudonym represents a joint collaboration by two or more
persons each of whom also write under their real name and there are items in
the catalog under the real names (RDA 9.2.2.8).**

Create one NAR for the joint pseudonym. Use the joint pseudonym as the basic heading.
Also, create one NAR each for the associated names. On the joint pseudonym NAR
provide a 500 field (see-also reference) for each of the associated real names.

**Text in 663 of the joint pseudonym.** In the joint pseudonym NAR [ **See
Bookmark Q2** for information on the basic heading technique] provide a 663 note
field with the sample text below. The text may be adjusted to fit the situation:

```
Joint pseudonym of [names of other persons using the pseudonym given in
direct order]. For works of these authors written under their own names, search
also under: $b [established form of name] $b [established form of name]
```
**Text in 663 note of the persons using joint pseudonym.** In each of the NARs
created for the persons using the joint pseudonym provide a 663 note with the sample
text below. The text may be adjusted to fit the situation:

```
For work of this author written in collaboration with [name of the collaborator in
direct order], search also under: $b [established form of the joint pseudonym]
```
```
See Bookmark Example 1.
```
**A1.6. The pseudonym is used by several persons working independently of
each other.**

Create one NAR for the shared pseudonym and one NAR for each individual using the
same pseudonym. The NARs for the names associated with the shared pseudonym are
established regardless of whether the persons using the same pseudonym wrote,
performed, sang, painted, etc. under that name. Treat the shared pseudonym NAR as
the basic heading [See Q2 for information on basic heading technique].
**See Bookmark Example 1.**

```
Text in 663 note of the shared pseudonym NAR. In the shared pseudonym NAR
provide a 663 note field with the sample text provided below. The text may be adjusted
to fit the situation:
```
```
Pseudonym used by multiple persons, for works of authors written under their
own or other names, search also under: $b [established form of name] $b
[established form of name] $b [established form of name]
```
**Text in 663 note of NAR persons sharing pseudonym.** In each of the NARs
created for the persons using the shared pseudonym provide a 663 note with the
sample text provided below. The text may be adjusted to fit the situation:

```
For works of this author written under other names, search also under: $b
[established form of the shared pseudonym]
```

**Q2. How do I decide which name to choose as the basic heading when
creating NARs for a person with multiple pseudonyms? (DCM Z1 663—
Complex see-also reference—Names)**

**A2.** Choose as the basic heading the predominant (most commonly found) form of
name. If it is not possible to determine a predominant form choose the real name as
the basic heading.

In the NAR chosen as the basic heading include the following MARC 21 tags:
 Add a 500 field (see-also reference) for each of the associated names.
 Add to each 500 field a subfield $w coded “nnnc”.
 Add a 663 note field with text explaining the relationship in subfield $a.
[See A1.3, A1.5, and A1.6 in this FAQ for sample text to use]
 In subfield $b of the 663 note list all the associated names in the
established form as provided in the see-also references, precede each
additional name with a subfield $b; do not include any other subfields; do
not end the 663 field with a full stop.

In the NAR of each of the associated names include the following:
 Add a 500 field see-also reference linking to the name chosen as the
basic heading.
 Add a subfield $w coded “nnnc” to the 500 field.
 Add a 663 note field with text explaining the relationship to the basic
heading in subfield $a.
 In the 663 note subfield $b give only the name in the 100 (name heading)
of the basic heading NAR.

**Q3. Is it required to make a NAR for every pseudonym associated with a
person? Some persons purport to have ten or more pseudonyms but in my
catalog we only have works under one or two of those names – are there
limits set on the number of NARs required? (DCM Z1 667 Cataloger Note
section)**

**A3.** RDA does not set any limits on how many names should be created for
persons using pseudonyms. In a shared environment it can be assumed that all
users of the database would benefit from authority work performed by others. This is
especially true of public libraries which may have items under each name. However,
given the reality of dwindling resources for creating NARs, catalogers may exercise
judgment and limit the number of NARs created for authors with a large number of
pseudonyms to just those pseudonyms for which there are works in the catalog
and then document the decision in a 667 note.
Once a decision is made to limit the number of NARs, add a 667 note listing all
the names not established following the suggested text:

Pseudonyms not found on published works: [list of identities not established]


```
The 667 note will explain that not all pseudonyms have NARs created for them;
however, any name listed may be established when needed and deleted from the 667.
See Bookmark Example 3
```
```
Note that any name recorded in the 667 field may not be used in a 400 field as a
see reference. Pseudonyms are considered to be the name of a different identity that
a person wishes to assume for whatever reason (e.g., political, commercial, contractual)
and is therefore not eligible to be used as a variant. If access to a different named
identity is important, a separate NAR should be made. Do not consider that variant
forms of a person’s name are pseudonyms unless there is explicit evidence.
```
**Q4. Should the 663 note technique also be used in a corporate name NAR when
providing 500 see-also references for the members of a group? (RDA Chapter 30)**

```
A4. No, the 663 note technique is only used to link personal names (100 field) to
personal names ( 500 field). When linking the personal name of a musician to a musical
group the linking 500 fields are constructed as simple see-also references. The same
is true for the personal names of members of any group, heads of state, etc. RDA
catalogers may choose to use Appendix K relationship designations to relate corporate
names with personal names but a 663 note is not used. See Bookmark Example 4
```
**Q5. Can the 663 note be used without coding the 500 field with subfield $w nnnc?
(MARC 21 Format for Authority Records, 663 field)**

```
A5. No, the 663 note must have a corresponding 500 field (see-also reference) with a
subfield $w coded nnnc. The subfield $w should only be used in the see-also reference
(500 field) of a NAR that contains a 663 note.
```
**Q6. What about creating NARs for non-contemporary persons? Where is the
guidance?**

```
A6. Under RDA there is no contemporary vs. non-contemporary limitation on creation
of separate NARs for each name a person uses. See Bookmark Example 6
```
**Q7. What about variants of the real name used concurrently by authors?**

```
A7. If an author uses variants of their real name concurrently (as opposed to
abandoning one real name in favor of another) and this usage can be ascribed to the
fact that works written under one name are in different subject areas from works written
under other name(s), treat the case in the same way as pseudonyms and follow the
response in A1 in this FAQ for the details of using multiple headings. Note: apply this
interpretation only in retrospect, after information received from publications, etc., has
begun to provide the necessary evidence and this evidence is clear or in cases where
the author has declared that intent. See Bookmark Example 7
```

**Q8. How do I handle a situation when a pseudonym conflicts with another name?
Do I create an undifferentiated NAR, or add the name to an undifferentiated NAR if
it already exists?**

```
A8. Although RDA recognizes the existence of undifferentiated personal name authority
records (RDA 8.11), the Program for Cooperative Cataloging (PCC) has implemented a
policy that prohibits the establishment of new undifferentiated personal name authority
records coded RDA, and prohibits the addition of new identities to existing
undifferentiated personal name authority records. When a pseudonym conflicts with
another name, one of the additions in RDA 9.19.1.2 – 9.19.1.8 should be applied to the
pseudonym in order to create a unique authorized access point.
See Bookmark Example 8.
```
**Q9. How do I handle LC classification numbers: Do I add the same LCC (053) on
each NAR of a pseudonym? What if the pseudonym is used on non-literary
works?**

# A9. Consult LC’s Classification and Shelflisting Manual, Section F632 for

```
guidance. A quick response to this question is that Paragraph 1.d in Section
F63 2 states: “... Class works by or about an author who writes under several
pseudonyms in the single number tha t has been establishe d for that author,
regardless of the name under which the work being cataloged has been
entered.” Paragraph 6 Adding literary author numbers to name authority records
provides the following guidance: “... For authors who write literary works under
more than one name and who have authority records for each name, a 053 field
is added to each record. ...”
If an author uses a pseudonym for non-literary works LCC (053) numbers are not
added to the NAR for that pseudonym.
```

## EXAMPLES:

# Note: the following examples do not show the complete reference structure and no 670

# information is provided – only relevant or sufficient information to demonstrate the point

# has been included.

**Examples in response to question 1:
Example 1.1:** The person uses one pseudonym and never uses the real name - One
NAR

```
100 1# $a Quinn, Julia, $d 19 70 -
400 1# $a Pottinger, Julie Cotler, $d 19 70 -
```
```
The person uses only pseudonym; real name is a 400 see reference.
```
```
Example 1.2: Person uses both the real name and one pseudonym - Two NARs; real
name is added as a simple 500 see-also reference.
```
```
100 1# $a Sandford, John, $d 1944 Feb. 23-
500 1# $a Camp, John, $d 1944 -
```
```
100 1# $a Sandford, John, $d 1944 Feb. 23-
500 1# $w r $i Real identity: $a Camp, John, $d 1944-
```
```
Reciprocal NAR is made with simple 500 see-also.
```
```
100 1# $a Camp, John, $d 1944-
500 1# $a Sandford, John, $d 1944 Feb. 23-
```
```
100 1# $a Camp, John, $d 1944-
500 1# $wr $i Alternate identity: $a Sandford, John, $d 1944
Feb. 23-
```
```
Example 1.3: The person uses more than one pseudonym but may or may not use the
real name – 3 or more NARs – Apply basic heading technique.
```
```
Choose a basic heading – use a 663 note with the sample text and list all the
names to be linked. Precede each name with a subfield $b but do not add any
subfields in the name portion. Add a 500 field for each name and use a subfield
$w coded “nnnc” in each 500 field. Create NARs for each 500 and refer back
only to the name on the basic heading NAR.
```
```
100 1# $a Barbet , Pierre
500 1# $w nnnc $a Avice, Claude, $d 19 25 -
500 1# $w nnnc $a Maine, David
500 1# $w nnnc $a Sprigel, Oliver, $d 1925-
663 ## $a For works of this author written under other names,
search also under: $b Avice, Claude, 1925- $b Maine,
David; $b Sprigel, Olivier, 1925-
```

```
In the NARs created for each name used by the author the text of the 663 note
will direct the user only to the name on the basic heading NAR. The 500 see-
also reference for the basic heading contains a subfield $w coded “nnnc”
```
```
100 1# $a Avice, Claude, $d 1925-
500 1# $w nnnc $a Barbet, Pierre
663 ## $a Works by this author are identified by the name used
in the item. For a listing of other names used by this
author, search also under $b Barbet, Pierre
```
```
100 1# $a Maine, David
500 1# $w nnnc $a Barbet, Pierre
663 ## $a Works by this author are identified by the name used
in the item. For a listing of other names used by this
author, search also under $b Barbet, Pierre
```
```
100 1# $a Sprigel, Oliver, $d 1925-
500 1# $w nnnc $a Barbet, Pierre
663 ## $a Works by this author are identified by the name used
in the item. For a listing of other names used by this
author, search also under $b Barbet, Pierre
```
**Example 1.4:** The pseudonym represents a joint collaboration by two or more persons
and the catalog does not contain items by those persons under their real names – One
NAR. If a mixture of used and unused real names apply a combination of examples 1.
and 1.5 as needed.

```
100 1# $a Rosslyn, Virginia
400 1# $a Rivenbark, Isabelle A.
400 1# $a Luna, Claire D.
670 ## $a Cat power, 2001: $b t.p. (Virginia Rosslyn) back flap
(Virginia Rosslyn is the pseudonym of Isabelle A.
Rivenbark and Claire D. Luna)
```
```
100 1# $a Agi, Tadashi, $d 1962-
400 1# $a Kibayashi, Yuko
500 1# $w nnnc $a Kubayashi, Shin, $d 1962-
663 ## $a Joint pseudonym of Yuko and Shin Kibayashi. For
works of these authors entered under their own or other
names search also under: $b Kibayashi, Shin, 1962-
670 ## $a Kami no shizuku, 2005: $b t.p. (Agi Tadashi)
```

**Example 1.5:** The pseudonym represents a joint collaboration by two or more persons
each of whom write under their real name and there are items in catalog under the real
names – Multiple NARs

```
Use the joint pseudonym as the basic heading NAR and make reciprocal NARs for
the name of each of the persons using the joint pseudonym.
```
```
100 1# $a Alexander, Hannah
500 1# $w nnnc $a Hodde, Cheryl
500 1# $w nnnc $a Hodde, Melvin
663 ## $a Joint pseudonym of Cheryl Hodde and Melvin Hodde.
For works of these authors written under their own
names, search also under: $b Hodde, Cheryl $b Hodde,
Melvin
```
```
Note the sample text used for the basic heading NAR and the text on each of the
reciprocal NARs.
```
```
100 1# $a Hodde, Cheryl
500 1# $w nnnc $a Alexander, Hannah
663 ## $a For works of this author written in collaboration with
Melvin Hodde, search also under: $b Alexander, Hannah
```
```
100 1# $a Hodde, Melvin
500 1# $w nnnc $a Alexander, Hannah
663 ## $a For works of this author written in collaboration with
Cheryl Hodde, search also under: $b Alexander, Hannah
```
**Example 1.6:** The pseudonym is used by several persons working independently of
each other. Multiple NARs:

```
Use the shared pseudonym as the basic heading. List all users of the name in the
663 note. Create a reciprocal NAR for the name of each person using the shared
pseudonym; these persons may or may not have works issued under that name.
```
```
100 1# $a Meadows, Daisy
500 1# $w nnnc $a Bentley, Sue, $d 1951-
500 1# $w nnnc $a Chapman, Linda
500 1# $w nnnc $a Dhami, Narinder
500 1# $w nnnc $a Mongredien, Sue
663 ## $a Pseudonym used by multiple persons. For works by
these authors written under their own or other names,
search also under: $b Bentley, Sue $b Chapman, Linda
$b Dhami, Narinder $b Mongredien, Sue
```

```
NARs for each name are made with a 500 see-also reference with subfield $w
coded nnnc and a 663 note pointing only to the basic heading NAR.
```
```
100 1# $a Bentley, Sue, $d 1951-
500 1# $w nnnc $a Meadows, Daisy
663 ## $a For works of this author written under other names,
search also under: $b Meadows, Daisy
```
```
100 1# $a Chapman, Linda
500 1# $w nnnc $a Meadows, Daisy
663 ## $a For works of this author written under other names,
search also under: $b Meadows, Daisy
```
```
100 1# $a Dhami, Narinder
500 1# $w nnnc $a Meadows, Daisy
663 ## $a For works of this author written under other names,
search also under: $b Meadows, Daisy
```
```
100 1# $a Mongredien, Sue
500 1# $w nnnc $a Meadows, Daisy
663 ## $a For works of this author written under other names,
search also under: $b Meadows, Daisy
```
**Example in response to question 3:** The person has a large number of pseudonyms

- Multiple NARs

```
The person has a large number of pseudonyms; basic heading is identified and
663 note technique is used; 500 see-also references with subfield $w coded nnnc
made for names found in catalog and a 667 note is used to show that others
were not established. [Set of reciprocal NARS not given for this example]
```
```
100 1# $a Mullen, Frederic
500 1# $w nnnc $a Durand, Émil
500 1# $w nnnc $a Lemieux, Anton
500 1# $w nnnc $a Lessoné, Bertand
500 1# $w nnnc $a Lind, Gustave
500 1# $w nnnc $a Morel, Jean $c (Musician)
663 $a For works of this author written under other names,
search also under: $b Durand, Émil $b Lemieux, Anton
$b Lesonné, Bertand $b Lind, Gustave $b Morel, Jean,
(Musician)
667 ## $a Pseudonyms not found on published works: Léon
Adam, John Ashton, Eileen Ashton, Paul Beaupré ...
```

**Examples in response to question 4** : 663 note technique not used to link corporate
name (110 Heading-Corporate name) with see-also references linking to the personal
name(s) (500 field).

```
Corporate name with 500 field (simple see-also references) linking to all the
associated personal name NARs.
```
```
110 2 # $a Crosby, Stills, Nash & Young
500 1# $a Crosby, David, $d 1941-
500 1# $a Stills, Stephen
500 1# $a Nash, Graham
500 1# $a Young, Neil, $d 1945-
```
```
NARs for each personal name (100 Heading-Name) with a 51 0 field (simple see-
also reference) linking to the corporate name on each NAR.
```
```
100 1# $a Crosby, David, $d 1941-
510 2# $a Crosby, Stills, Nash & Young
```
```
110 1 # $a Stills, Stephen
510 2 # $a Crosby, Stills, Nash & Young
```
```
110 1 # $a Nash, Graham
510 2 # $a Crosby, Stills, Nash & Young
```
```
110 1 # $a Young, Neil, $d 1945-
510 2 # $a Crosby, Stills, Nash & Young
```
Example 4.1:
RDA catalogers may choose to add Appendix K relationship designators to relate
a group member to the corporate name

```
110 2# $a Crosby, Stills, Nash & Young
500 1# $w r $i Member: $a Crosby, David, $d 1941-
500 1# $w r $i Member: $a Stills, Stephen
500 1# $w r $i Member: $a Nash, Graham
500 1# $w r $i Member: $a Young, Neil, $d 1945-
```
```
RDA Appendix K used to relate each personal name to the corporate entity [only
one example shown here]
```
```
100 1# $a Crosby, David, $d 1941-
510 2# $w r $i Corporate body: $a Crosby, Stills, Nash & Young
```

**Examples in response to question 6** : Non-contemporary author uses more than one
name for separate bibliographic identities – Separate NARs

```
100 1# $a Dodgson, Charles Lutwidge, $d 1832- 1898
500 1# $a Carroll, Lewis, $d 1832- 1898
```
```
100 1# $a Carroll, Lewis, $d 1832- 1898
500 1# $a Dodgson, Charles Lutwidge, $d 1832- 1898
```
**Examples in response to question 7** : Variations of a real name used concurrently –
Multiple NARs

```
100 1# $a Lasky, Kathryn
500 1# $w nnnc $a Knight, Kathryn Lasky
500 1# $w nnnc $a Swann, E. L.
663 ## $a For works by this author written under other names,
search also under: $b Knight, Kathryn Lasky $b Swann,
E. L.
```
## 670

```
## A baby for Max, 1984: ‡b CIP t.p. (Kathyrn Lasky) author
info. (Kathryn Lasky Knight; uses pen name E. L. Swann)
670 ## Tel. call to the author, July 17, 1986 ‡b (author will
continue to write children's works under "Kathryn Lasky"
and adult works under "Kathryn Lasky Knight" and wants
LC to use separate headings for each type of work)
```
```
100 1# $a Knight, Kathryn Lasky
500 1# $w nnnc $a Lasky, Kathryn
663 ## $a Works by this author are identified by the name used
in the item. For a listing of other names used by this
author, search also under: $b Laskey, Kathryn
670 ## Atlantic circle, 198 6 : ‡b t.p. (Kathyrn Lasky Knight)
670 ## Tel. call to the author, July 17, 1986 ‡b (author will
continue to write children's works under "Kathryn Lasky"
and adult works under "Kathryn Lasky Knight" and wants
LC to use separate headings for each type of work)
```
```
100 1# $a Swann, E. L.
500 1# $w nnnc $a Lasky, Kathryn
663 ## $a Works by this author are identified by the name used
in the item. For a listing of other names used by this
author, search also under: $b Laskey, Kathryn
670 ## Night gardening, 1999: ‡b CIP t.p. (E.L. Swann) pub.
info. (pseudonym for Kathryn Lasky/Kathryn Lasky
Knight; will use this pseud. when writing major
commercial fiction for adults)
```

**Examples in response to question 8** : Pseudonym in conflict with existing
undifferentiated name – new pseudonym Anthea Lawson conflicts with an existing
undifferentiated heading representing other identities named Anthea Lawson: New NAR
created for the pseudonym with the application of RDA 9.19.1.5, Period of Activity of
the Person, to break the conflict:

```
100 1# $a Lawson, Anthea, $d active 2009
```
# 500 1# $w nnnc $a Lawrence, Anthea, $d 1967-

```
500 1# $w nnnc $a Dumbeck, Lawson
663 ## $a Joint pseudonym of Anthea Lawrence and Lawson
Dumbeck. For works of these authors written under their
own names, search also under: $b Lawrence, Anthea,
1967 - $b Dumbeck, Lawson
670 ## All he desires, c2009: $b t.p. (Anthea Lawson)
670 ## Romance wiki, viewed Oct. 26, 2010: $b (Anthea Lawson
is the joint pseudonym of Anthea Lawrence and Lawson
Dumbeck)
```
**Example 8.1** : NAR for Lawrence, Anthea, 1967-with 500 see-also reference to the
pseudonym in the new NAR.

```
100 1# $a Lawrence, Anthea, $d 1967-
500 1# $w nnnc $a Lawson, Anthea, $d active 2009
663 ## $a For works of this author written in collaboration with
Lawson Dumbeck, search also under: ‡b Lawson,
Anthea, active 2009
670 ## Passionate, 2008 ‡b t.p. (Anthea Lawson)
670 ## Anthealawson.com website, Nov. 17, 2010: ‡b (Anthea
Lawson; are a husband and wife creative team living in
the Pacific Northwest. Their first novel, Passionate, was
released from Kensington books in October 2008;
Musicians as well as writers, the two have recorded
many CDs, including several with their Celtic band
Fiddlehead)
```
**Example 8.2** : NAR for Dumbeck, Lawson with 500 see-also reference to the
pseudonym in the new NAR.

```
100 1# $a Dumbeck, Lawson
500 1# $w nnnc $a Lawson, Anthea, $d active 2009
663 ## $a For works of this author written in collaboration with
Anthea Lawrence, search also under: ‡b Lawson,
Anthea, active 2009
670 ## Passionate, 2008 ‡b t.p. (Anthea Lawson)
670 ## Anthealawson.com website, Nov. 17, 2010: ‡b (Anthea
Lawson; are a husband and wife creative team living in
the Pacific Northwest. Their first novel, Passionate, was
released from Kensington books in October 2008;
Musicians as well as writers, the two have recorded
many CDs, including several with their Celtic band
Fiddlehead)
670 ## CD Baby website, accessed via Google, Nov. 17, 2010,
"Fiddlehead" ‡b (Fiddlehead, hailed as one of the finest
Celtic groups in the Northwest ... features Anthea
Lawrence on fiddle and vocals, Audra Poor on Uillean
pipes, flute, and whistle, and Lawson Dumbeck on guitar,
banjo, bouzouki, and bodhran)
```


