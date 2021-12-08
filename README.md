This Readme will be updated whenever `Readme.Rmd` or `test.csv` is
changed. To see Eli’s presentation go
[HERE](https://htmlpreview.github.io/?https://github.com/nmfs-openscapes/12-07-21-GitHub-Actions/blob/main/Intro.html)
or to the `Intro.Rmd` file.

A table of data
---------------

    a <- read.csv("test.csv")

    knitr::kable(a)

<table>
<thead>
<tr class="header">
<th style="text-align: left;">name</th>
<th style="text-align: right;">number</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Eli</td>
<td style="text-align: right;">10</td>
</tr>
<tr class="even">
<td style="text-align: left;">Yuan</td>
<td style="text-align: right;">57</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Adele</td>
<td style="text-align: right;">22</td>
</tr>
<tr class="even">
<td style="text-align: left;">Patrick</td>
<td style="text-align: right;">17</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Martina</td>
<td style="text-align: right;">35</td>
</tr>
<tr class="even">
<td style="text-align: left;">Emilio</td>
<td style="text-align: right;">75</td>
</tr>
</tbody>
</table>
