# goldenrod-eurosta
Data on goldenrod galls from undergraduate evolution and ecology labs.

## Where does this data come from?

The data in this repo come from various lab courses that talked about natural selection on traits, or the ecology of parasitic and predatory interactions. Goldenrod stems were collected from several areas between October-January, and students dissected them in class during the school year. Two of the files come from courses that Raffica La Rosa was the teaching assistant for at Michigan State University for Ecology Lab (ZOL355L/PLB355L), and one dataset comes from an Evolution (EBIO4600) course at the University of Colorado Boulder, taught by Nancy Emery, with assistance from R. La Rosa.

## General methods

Students learned about the natural history of the parasitic goldenrod gallfly, and the various parasites and predators that prey upon it. The information presented was taken directly, or adapted from, Warren G. Abrahamson's [website](http://www.facstaff.bucknell.edu/abrahmsn/solidago/main.html).

Students then made hypotheses and predictions about relationships between the traits of the goldenrod gall (often considered a trait of the gallfly) and the survival of the gallfly larva, or it's demise by a number of potential actors (wasps, birds, or beetle). Hypotheses are easily made in the context of evolutionary questions about natural selection (effects of traits on survival), or ecological questions that focus on the correlations between factors.

Galls were carefully dissected latitudinally, in line with the main stem, and the contents were observed.

## Contributing to this dataset

If you have taught this lab, or a variant of it, and would like to add your data so that others can use it, you may open a pull request. Your pull request should contain a CSV file of the data, edits to the README.md file with any new headers added to the table below, and your name and university affiliation added to the list of contributors.

## Description of headers:

| Header | Description |
| ------ | ----------- |
| beetle?| Is the beetle predator (_Mordellistena convicta_) present? y=yes, n=no |
| bird_predation? | Is there evidence of bird predation by chickadees or woodpeckers? y=yes, n=no, 1=yes, 0=no |
| chamber_diameter_mm | The diameter of the space in the gall where the gallfly larva was/is residing. |
| collection_date | The date or season when the goldenrod stems were collected. |
| collection_site | The site of the goldenrod population. |
| early_wasp? | Is there evidence of the early smaller parasitoid wasp (_Eurytoma obtusiventris_)? y=yes, n=no |
| gall_circumference_mm | The circumference of the gall along the horizontal/transverse/axial plane. |
| gall_contents | The contents of the gall chamber. |
| gall_diameter_mm | The diameter (width) of the entire gall (perpendicular to the stem). ![Figure](https://github.com/rjlarosa/goldenrod-eurosta/blob/master/CU_gall_traits.jpg). |
| gall_height_mm | The hight of the entire gall (inline with the stem). ![Figure](https://github.com/rjlarosa/goldenrod-eurosta/blob/master/CU_gall_traits.jpg). |
| gall_id | Each group had a collection of galls that they numbered for data collection. |
| gall_wall_thickness_mm | The thickness of the gall wall from the chamber to the outer surface. |
| gallfly_larva_length_mm | The length of the gallfly larva, but may actually be the length of the pupa. |
| group | The group of students that worked together to collect a subset of the data. |
| hard_wall_thickness_mm_1 | The thickness of the hard outer layer of the gall on one side. Trait A in ![Figure](https://github.com/rjlarosa/goldenrod-eurosta/blob/master/CU_gall_traits.jpg). |
| hard_wall_thickness_mm_2 | The thickness of the hard outer layer of the gall on the other side. Trait A in ![Figure](https://github.com/rjlarosa/goldenrod-eurosta/blob/master/CU_gall_traits.jpg). |
| hard_wall_thickness_mm_ave | The average of the thickness of the hard outer layer of the gall. Trait A in ![Figure](https://github.com/rjlarosa/goldenrod-eurosta/blob/master/CU_gall_traits.jpg). |
| intact_gallfly_larva? | Does the gall contain an intact gallfly larva? y=yes, n=no, 1=yes, 0=no |
| late_wasp? | Is there evidence of the late larger parasitoid wasp (_Eurytoma gigantea_)? y=yes, n=no |
| parasitoid-type | What consumed the gallfly larva? |
| parasitoid? | Is there evidence of a parasitoid (or parasite)? y=yes, n=no, 1=yes, 0=no |
| pith_wall_thickness_mm_1 | The thickness of the pithy inner layer of the gall on one side. Trait B in ![Figure](https://github.com/rjlarosa/goldenrod-eurosta/blob/master/CU_gall_traits.jpg). |
| pith_wall_thickness_mm_2 | The thickness of the pithy inner layer of the gall on the other side. Trait B in ![Figure](https://github.com/rjlarosa/goldenrod-eurosta/blob/master/CU_gall_traits.jpg). |
| pith_wall_thickness_mm_ave | The average thickness of the pithy inner layer of the gall. Trait B in ![Figure](https://github.com/rjlarosa/goldenrod-eurosta/blob/master/CU_gall_traits.jpg). |
| plant_height_to_gall_base_cm | The height of the plant from near the ground to the base of the gall. |
| plant_height_with_gall_cm | The height of the entire plant, that contains a gall, from the ground to the top |
| plant_height_without_gall_cm | The height of the entire plant, that does not contain a gall, from the ground to the top |
| section | The lab section for the course. |
| stem_width_2cm_below_gall | The width of the goldenrod stem 2cm below the gall. |

## Description of collection sites:

| Site               | Description    |
| ------------------ | -------------- |
| kbs                | Kellogg Biological Station (MSU) in Hickory Corners, MI. Galls collected by water tower. |
| Gladwin, MI        | Collected on private property. |
| East Lafayette, IN | Collected west of Purdue University |

## License

The data here is protected under the Creative Commons Attibution 4.0 International license. This license permits almost any use, subject to providing credit and license notice. Frequently used for media assets and educational materials. The most common license for Open Access scientific publications. Description from [choosealicense.com](https://choosealicense.com/licenses/cc-by-4.0/).

## Contributors

| Name | Institution where data was collected | Year of collection | File name | Other |
| ---- | ------------------------------------ | ------------------ | --------- | ----- |
| Raffica La Rosa | Michigan State University | 2012 | MSU_ZOL355L_FS12.csv | --- |
| Raffica La Rosa | Michigan State University | 2013 | MSU_ZOL355L_SS13.csv | --- |
| Nancy Emery and Raffica La Rosa | University of Colorado Boulder | 2017 | CU_EBIO4600_FS17.csv | --- |
