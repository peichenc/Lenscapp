<b>Lenscapp</b>
========

<i>Automatic</i> hashtags for your social app

<b>Hashtags for:</b><br>
<ul>
     <li>Holidays (all countries)<br>
     <li>National Parks (US, Canada)<br>
     <li>Hiking trails (US)<br>
     <li>Events (US)<br>
</ul>
<br>     
<b>Technology:</b><br>
Uses your location <i>and</i> time to determine event<br><br>
<dl>
<dt>For example:<br>
<dd>37.806569°N, -122.429130°W = San Francisco<br>
<dd>That same location on 2000-07-04 = Independence Day<br>
</dl>
<br>
<b>RESTful api</b><br>
To look up keywords & hashtags: <br>
/keywords/find<br><br>
<dl>
<dt><i>Parameters</i><br>
<dd>latitude: (double) -90 ~ +90<br>
<dd>longitude: (double) -180 ~ +180<br>
<dd>date: In the format of YYYY-MM-DD HH:mm:ss<br>
<dd>appID: Assigned.  Please contact us at the email address below to get your free key<br>
<dd>verbose=true (always set this to true)
</dl>
<br>
<b>Results in JSON format</b><br>
{<br>
    "COUNTRY_NAME": [<br>
        "United States of America"<br>
    ],<br>
    "CITY": [<br>
        "California ; Placer ; United States ; USA"<br>
    ],<br>
    "EVENT": [<br>
        "Halloween"<br>
    ],<br>
    "PROVINCE_OR_STATE": [<br>
        "California ; United States of America ; USA"<br>
    ],<br>
    "HASHTAG": [<br>
        "#Halloween"<br>
    ],<br>
    "ALL": [<br>
        "California ; Halloween ; Placer ; United States ; United States of America ; USA"<br>
    ]<br>
}<br>
<br>
<b>Support</b><br>
For more information or to get an API key, please contact us at support@lenscapp.com<br>

