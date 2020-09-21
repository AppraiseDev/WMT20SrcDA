# WMT20SrcDA

Code and issue tracker for WMT20 source-based DA campaigns

## Updates

- 20200916: Added Frequently Asked Question section
- 20200910: Added description of source-based DA
- 20200909: Accounts are *live now*, please contact `{chrife,rogrundk,tomkocmi}@microsoft.com` about your accounts
- 20190902: [WMT20.appraise.cf](http://wmt20.appraise.cf) goes live

## TL;DR

- WMT20 will feature source-based direct assessment (DA)
- Evaluation will be based on document-level annotation
- Source-based DA will focus on non-English target languages
- Please use the [Github issue tracker](https://github.com/AppraiseDev/WMT20SrcDA/issues) to report any problems

## Timeline

- 9/09: eval plan online on Github
- 9/10--9/17: research teams request accounts
- (from) 9/10: accounts shared with research teams
- 9/10: annotation starts
- 10/10: annotation ends

## Campaign overview

### How will the annotation work?

Annotations will be collected in Appraise, implementing document-level,
source-based direct assessment. For every language pair, there will be a
pre-generated amount of annotations tasks (``HITs''). We will generate
anonymised accounts which are pre-assigned to exactly two annotation tasks.

### How much annotation work is needed?

One task involves approximately 100 judgements. Based on previous WMT evaluation
campaigns, the average annotation time for one task is 30 minutes. 

Each research team is expected to contribute **eight hours of annotation work
per primary system** submission. This translates to **16 completed tasks**
in total, on Appraise, per primary system.

### Who can be an annotator?

The source-based evaluation campaign is run for non-English target languages.
This means that we look for native speakers of the non-English target language
who are also proficient in English and can assess translation quality from
English into their native language.

### How are accounts distributed?

Account distribution is based on first-come, first-served basis, i.e., once
an account is marked as ``assigned'' to a team you cannot claim it anymore.
Each research team should designate a team leader who is then responsible to
reserve the required amount of accounts for their team.

Each research team will be provided with 8 accounts, i.e. 16 annotation tasks,
per primary system the team has submitted.

### Where can I claim my account?

Please contact `{chrife,rogrundk,tomkocmi}@microsoft.com` to request your accounts.

### How can I sign into Appraise?

For each account, we provide a **single sign-on (SSO) URL**. This allows you
to sign into Appraise with a single click on the URL, making access very easy.

### What information do you store about me?

There is no personal information attached to the annotation accounts. We
capture your assessments and related metadata, such as annotation start and
end time as well as duration per single assessment.

### How does source-based DA work?

This year the campaign features a document-level annotation view with the
entire document presented on a single screen in two columns. The left column
has source sentences and the right column has corresponding candidate
translations (see the screen), that you will be scoring using a slider.

![Screenshot of WMT20](/images/screen_wmt20.png)

The annotation process consists of scoring individual sentences one-by-one and
then assigning a single score for the entire document. Assigning the
document-level score (the slider at the very bottom of the page) becomes
available after all previous sentences are scored.

Submitting a score will automatically move the annotation to the next sentence
and open a new slider. A dot on the right side of the translated sentence
roughly indicates the assigned score: a reddish dot means a lower score (worse
translation), and a greenish dot means a higher score (better translation). The
tick means that the score has been successfully collected by the server and the
progress is saved (i.e. the web page can be reloaded without loosing the
progress made on the current document). If you decide to change the assigned
score, it is possible to do so at any point of the annotation process by
clicking on the sentence text to expand a slider, updating the score, and
clicking 'Update'. When the document-level score is submitted, the annotation
process continues with the next document until all documents assigned to your
account are annotated.

### How can I report problems?

Please use the [Github issue tracker](https://github.com/AppraiseDev/WMT20SrcDA/issues)
to report any problems. You can also contact us via ``{chrife | rogrundk | tomkocmi } [at] microsoft [dot] com``.

## Frequently asked questions

### Are there any reference based annotations or XXX into English translations?

No, this campaign is source based DA for non-english target language only.

### Is the 10th October deadline final?

Unfortunately yes. In uttermost case, when you are sure that you cannot meet the deadline, try to finish as many annotations as possible and let us know. However, please try to avoid this as much as possible.

### Do I need to annotate languages of my primary system submissions?

No, that is not necessary. We balance annotations accross teams that speak various languages. You can annotate any language pair in which you are proficient.

### Why does some documents in annotation are same/similar?

Various systems have translated the same document, therefore similar translations are annotated. Furthermore, it may happen that the same document occurs in multiple tasks.
