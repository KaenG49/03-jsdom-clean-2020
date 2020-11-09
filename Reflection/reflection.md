# Reflection

This exercise relies on Wikipedia to turn a simple text table into "linked data". In the following exercies, you'll be asked to think about where this model can and cannot be replicated. You will probably want to use markdown source blocks and tables in some of your ansers. You can create a table with vertical pipes:

```markdown
Header 1 | Header 2
---------+---------
Content cell 1 | Content Cell 2
Content Row 2 | Content Row 2
```

The block above uses fenced code blocks to show the table syntax; you might use code blocks for other purposes in this reflection, as well.

## Question 1 (150 words)

#### Our underlying dataset was a list of political leaders. Describe another possible dataset which could use Wikipedia in the same way. Give an example of a possible Javascript object description of one record in the dataset, using the Javscript objects from Parts 1 and 3 as a starting point.

Another possible dataset could be a list of all the engagements of a nation in a war. Similiar to our javascript objects in the assignment, the object below could be a part of a list of all the Second World War engagements of Canada. According to wikipedia, there are 73 different engagements during World War Two that involve Canada. In the hypthetical javascript object below, the first engagement is depicted.

let OpAbercrombie = {
ame: 'Operation Abercrombie',
beginning: '21 April 1942',
end: '22 April 1942',
location: 'Hardelot, France'
canadianunits: 50,
outcome: 'objectives unmet'
description: "Allied reconnaissance mission to Hardelot, France in 1942. Objectives of the mission were not fulfilled.'

## Question 2 (150 words)

#### Now describe another dataset for which Wikipedia would **not** be as good a resource. What does this tell you about the limitations of Wikipedia? WHat kind of work would you need to do to make useful links for this dataset?

Wikipedia is extremely good at linking different kinds of qualitative and quantitative topics. However, datasets that rely on a lot of visual material may be better depicted on other platforms. If you are working on a project (e.g. a digital exhibition project) that requires an analysis of visual materials, such as 'Propaganda in Nazi Germany,' you will need a lot of visual material to expand on your topic. Although it is possible to add images and videos to Wikipedia via Wikimedia, Wikipedia datasets most certainly utilize text-based information more than media-based information. Therefore, Wikipedia is not a useful resource if you are looking for visual material. In order to improve these types of datasets, images from other websites could be anchored to Wikipedia articles. In the specific case of 'Propaganda in Nazi Germany,' images from other scholarly websites that depict historically accurate images/videos/artifacts could be anchored.

'https://en.wikipedia.org/wiki/Propaganda_in_Nazi_Germany'

## Question 3 (150 words)

#### Finally, what problems do you see with this tabular format? What are its limitations, and what do they suggest more broadly about the limitations of data-based historical/humanistic inquiry?

Data-based inquiry in the field of history is susceptible to be insufficient when qualitative information and discourse overpowers the quantitative material for a particular topic. Tabular data presentation may be suitable for superficial qualitative information (such as 'party affiliations' or 'years in office' for political leaders) or to get quick quantitative information (e.g. Allied casualties in WW1 with each row corresponding to a different participant). However, topics that require in-depth analysis may struggle if they are to be depicted in a tabular data format. If selected, the tabular format may look weird to show quantitative data regarding in-depth information. For example, if you decide to show "foreign soviet interventions," you may want to explain the reason behind the intervention, as just stating the 'intervened country' and the 'year of intervention' is not qualitatively rich. However, the reasons behind these interventions are in-depth, and a qualitatively rich answer would take more space than a conventional tabular data cell, deeming tabular format insufficient.

https://en.wikipedia.org/wiki/Foreign_interventions_by_the_Soviet_Union
