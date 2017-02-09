![logo](http://i.imgur.com/TAfhGeGm.png)

## Results & Evaluation

In order for the IATI Standard to facilitate shared learning, practitioners need access to **results and evaluation** information. Even access to a list of proposed outcomes and targets, without detailed results data, can be useful to understand the activities that might be relevant to learn from.

There are a variety of reasons why practitioners need this data, ranging from the desire to see which approaches worked and which didn’t, to the ability to map outcomes against locations and descriptions to identify when similar approaches had different outcomes. Regardless of the methods, the reason is always the same — to leverage the findings of others in pursuit of improving a proposed project.

There are a number of ways by which donors can publish project results and evaluations with the IATI Standard. They can either link to a document within the IATI XML and then code it as an evaluation (A07) or outcome report (A08), or publish the results as structured data. An example is below:

```XML
<result type="1">
    <title>
        <narrative>
            Drinking water transmission and distribution pipes constructed (km)
        </narrative>
    </title>
    <indicator measure="1">
        <title>
            <narrative>kilometers</narrative>
        </title>
        <period>
            <period-start iso-date="2005-01-01"/>
            <period-end iso-date="2016-12-31"/>
            <target value="57.40"/>
        </period>
        <period>
            <period-start iso-date="2016-01-01"/>
            <period-end iso-date="2016-12-31"/>
            <actual value="0.00"/>
        </period>
    </indicator>
</result>
```

To improve the availability of results and evaluations information, we need to do the following:

* Extract and convert pre-existing results data into IATI XML.

* Produce guidelines on what constitutes useful results and evaluations data, and to what extent it can be standardised among publishers.

<table>
  <tr>
    <td>Publication challenge</td>
    <td>User challenge</td>
  </tr>
  <tr>
    <td>Publish useful and comparable results and evaluations data. Parse target and results data from existing documents. </td>
    <td>Use results data to understand which approaches worked and which didn’t, enabling shared-learning and/ or further investigation. </td>
  </tr>
</table>



*"I want to know why people facing the same challenges are not responding in the same way to the same or similar approaches; and this is a key question from a researcher’s point of view. Why is this country or region behaving differently from another one?"* - Autumn Consultation, 2016
