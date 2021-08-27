## Scope

The purpose of this document is to identify specific technical terms (definitions and abbreviations) used within the GSF specifications. Having a common collection of definitions and abbreviations related to the GSF documents will;
- Ensure that the terminology is used in a consistent manner across GSF documents
- Provide the reader a friendly tool explaining the technical terms that are used across multiple documents
- Help the editors in using the terminology in a consistent manner across GSF specifications.

The definitions and abbreviations as given in this document are
- created by the GSF working groups or sub-groups, when the need for precise definition is identified, or
- imported from existing documentation (e.g. ITU, 3GPP, 3GPP2)

## References
### Normative References

```
The policy for reference lists is:
1. GSF documents listed should have at least one approved version – draft-only docs should not be referenced.
Exception exists for documents that will be approved with or after the referenced doc is approved (may be part of same enabler package). In short – approved docs should not reference unapproved docs.
2. When a reference is made to an GSF specification, then Green Software Foundation™ with the TM symbol (™) should 
be used in the description.
3. The name + version (no date) for GSF specifications are generally sufficient – dates should be used only if there is a specific reason to limit the usage.
4. References to other affiliate docs should similarly provide sufficient information to uniquely determine the needed document and should provide the appropriate source information.
5. The URL for GSF material (new GSF and affiliate) should always be http://www.[add link].
    
Models to use:
	[REFLABEL]	<General Model> "Ref Title", Ref information (source, date, id), URL:http//<ref-source>/ 
	[GSFDOC]	<GSF Model> "GSF Document Title",{ Version x.y,}Green Software Foundation™, GSF <docname>{    <version>}, URL:[ADD HERE] 
If there are no entries in the table – enter ‘none’ to be clear.

DELETE THIS COMMENT
```
<table>
  <caption>Normative References </caption>
  <tbody>
    <tr>
      <td><strong>[RFC2119]</strong></td>
      <td>"Key words for use in RFCs to Indicate Requirement Levels", S. Bradner, March 1997, URL:http://www.ietf.org/rfc/rfc2119.txt</td>
    </tr>
    <tr>
      <td><strong>[RFC5234]</strong></td>
      <td>"Augmented BNF for Syntax Specifications: ABNF", D. Crocker, Ed., P. Overell, Janury 2008, URL: https://tools.ietf.org/rfc/rfc5234.txt</td>
    </tr>
  </tbody>
</table>

```
Add/Remove reference rows as needed - DELETE This Row 
```

### Informative References

<table>
  <caption>Informative References </caption>
  <tbody>
    <tr>
      <td><strong>[GSFDICT]</strong></td>
      <td>"Dictionary for GSF Specifications", Version x.y, Green Software Foundation™, GSF-ORG-Dictionary-Vx_y: https://greensoftware.foundation
    </tr>
  </tbody>
</table>

```
Add/Remove references as needed - DELETE This Row
```

## Terminology and Conventions
### Conventions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC2119].

### Definitions

<table>
  <caption>Definitions</caption>
  <tbody>
    <tr>
	<td><strong>Committee Team</strong></td>
	<td>A group chartered by the Steering Committee to perform specific support tasks</td>
    </tr>
    <tr>
	<td><strong>Editor(s)</strong></td>
	<td>A member of a Working Group that is responsible to edit and maintain a document.</td>
    </tr>	  
    <tr>
	<td><strong>Epic</strong></td>
	<td>It is a component inside of a Work Package. It could be a feature, customer request or business requirement.</td>
    </tr>
    <tr>
	<td><strong>e-Vote</strong></td>
	<td>Electronic Vote.</td>
    </tr>
    <tr>
	<td><strong>Issue(s)</strong></td>
	<td>An important topic or problem for debate or discussion. Normally, in GSF Issues are tracked in Github.</td>
    </tr>	  
    <tr>
	<td><strong>Maintainer</strong></td>
	<td>A member of the Working Group or GSF staff support that performs maintenance tasks on behalf of the Working Group or Organization.</td>
    </tr>
    <tr>
	<td><strong>Member(s)</strong></td>
	<td>A person that belongs to a company that has signed GSF Membership Agreement and Charter(s) and have access to GSF resources.</td>
    </tr>	  
    <tr>
	<td><strong>Membership Agreement</strong></td>
	<td>A legal document that provides legal information about rights and obligations of being a member company of GSF.</td>
    </tr>
    <tr>
	<td><strong>Chairs</strong></td>
	<td>GSF member that has been selected by the Working Group as a coordinator for the Working Group activities.</td>
    </tr>	  
    <tr>
	<td><strong>Project Charter</strong></td>
	<td>A legal document that describes the GSF Project.</td>
    </tr>
    <tr>
	<td><strong>Pull Request</strong></td>
	<td>It indicates what changes are suggested to a branch in a repository on GitHub.</td>
    </tr>
    <tr>
	<td><strong>Release</strong></td>
	<td>It is the distribution of the final version of a document or application.</td>
    </tr>	  
    <tr>
	<td><strong>Review & Approval</strong></td>
	<td>A special process that is used to convey agreement or disagreement on a topic. </td>
    </tr>
    <tr>
	<td><strong>Semantic Versioning</strong></td>
	<td>It is a versioning scheme to convey backwards or not backwards compatibility of a release.</td>
    </tr>
    <tr>
	<td><strong>Source Code</strong></td>
	<td>A text listing of commands to be compiled or assembled into an executable computer program.</td>
    </tr>	  
    <tr>
	<td><strong>Specification(s)</strong></td>
	<td>An act of describing or identifying something precisely or of stating a precise requirement.</td>
    </tr>	  
    <tr>
	<td><strong>Steering Committee</strong></td>
	<td>A committee that decides on the priorities or order of business on GSF. </td>
    </tr>
    <tr>
	<td><strong>Supermajority Vote</strong></td>
	<td><i>Extracted from GSF 5.0.1 Member Agreement</i> means an affirmative vote of no less than 3/4 of Steering Members or Working Group Participants, as applicable, that have attended/participated in at least 50% of the last 4 meetings of the group conducting the vote, where each Steering Member or Working Group Participant will receive only 1 vote regardless of how many individuals from that party participate. To ensure the group is capable of making decisions, the voting requirement for attendance/participation of at least 50% of the last 4 meetings shall be waived if there have not yet been 4 meetings.
</td>
    </tr>
    <tr>
	<td><strong>Working Group</strong></td>
	<td>It is a group of experts working together to achieve predefined objectives. The group formalize its objectives and goals in a formal document, the Working Group Charter.</td>
    </tr>
    <tr>
	<td><strong>Working Group Chair</strong></td>
	<td>A person selected by the Working Group which primary role is to facilitate consensus-building among the group members.</td>
    </tr>	  
    <tr>
	<td><strong>Working Group Charter</strong></td>
	<td>A document that contains the scope, objectives, and goals of a particular group. </td>
    </tr>
    <tr>
	<td><strong>Work Package</strong></td>
	<td>It is a group of related tasks within a project. Each Work Package can be broken down into one or more Epics.</td>
    </tr>	  
  </tbody>
</table>

<table>
  <caption>Technical Terms</caption>
  <tbody>
    <tr>
	<td><strong>Green by Software</strong></td>
	<td>Using software to help achieve the sustainability goal of a specific domain or organization.</td>
    </tr>
    <tr>
	<td><strong>Green in Software</strong></td>
	<td>Optimizing software itself for better energy efficiency or reduced carbon emissions.</td>
    </tr>
    <tr>
	<td><strong>Speedup</strong></td>
	<td>The metric to measure the relative execution time of two programs.</td>
    </tr>  
    <tr>
	<td><strong>Greenup</strong></td>
	<td>The metric to measure the relative energy consumption of two programs. </td>
    </tr>  
    <tr>
	<td><strong>Powerup</strong></td>
	<td>The metric to measure the relative power consumption of two programs. </td>
    </tr>  
  </tbody>
</table>

### Abbreviations


<table>
<caption>Definitions</caption>
<tbody>
    <tr>
    <td>CWG</td>
    <td>Community Working Group</td>
   </tr>
    <tr>
    <td>GSF</td>
    <td>Green Software Foundation</td>
   </tr>
    <tr>
    <td>IPR</td>
    <td>Intellectual Property Rights</td>
  </tr>
   <tr>
    <td>IWG</td>
    <td>Innovation Working Group</td>
   </tr>
   <tr>
    <td>PR</td>
    <td>Pull Request</td>
  </tr>
   <tr>
    <td>SC</td>
    <td>Steering Committee</td>
  </tr>
   <tr>
    <td>SWG</td>
    <td>Standards Working Group</td>
   </tr>
   <tr>
    <td>SUP</td>
    <td>Supporting Document</td>
  </tr>	
   <tr>
    <td>TS</td>
    <td>Technical Specification</td>
  </tr>
    <tr>
    <td>TWG</td>
    <td>Trademark Working Group</td>
   </tr>
   <tr>
    <td>WG</td>
    <td>Working Group(s)</td>
   </tr>	
</tbody>
