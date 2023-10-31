# Ex04 Places Around Me

## DATE: 31/10/23

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
## index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Map</title>
</head>
<body>
    <img src="Map.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="school" title="school" href="a.html" coords="190,50,20" shape="rect">
        <area target="_blank" alt="hometown" title="hometown" href="b.html" coords="230,30,260,60" shape="rect">
        <area target="_blank" alt="govthospital"title="govthospital" href="c.html" coords="400,350,50" shape="rect">
        <area target="_blank" alt="busstand" title="busstand" href="d.html" coords="400,200,75" shape="rect">
        <area target="_blank" alt="policestaion" title="policestaion" href="e.html" coords="490,150,870,320" shape="rect">
    </map>
</body>
</html>
```
## a.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>SCHOOL</title>
</head>
<body bgcolor="ROSE">
</h1>
<h3 align="center">
<font color="blue"><b>DHARANI.MATRIC.HIGHER.SEC.SCHOOL.</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
SCHOOLS<ul>
<li>To impart proper and qualified training to teachers and give them an attractive salary and incentives so that they are not tempted to quit and look elsewhere for jobs.</li>
<li>Schools are organized into different levels, such as preschool, elementary, middle, and high school, to cater to students of varying ages and educational needs.</li>
<li>To Frame of syllabus and curriculum.</li>
<li>To set aims and objectives of education.</li>
</ul>
</font>
</p>
</body>
</html>
```
## b.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>HOME TOWN</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>MANNARGUDI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>HOME</b></font>
</h3>
<hr size="3" color="orange">
<p align="justify">

<ol type="1">
<li> Natives have a deep historical and cultural connection to the land they inhabit, often spanning generations or even millennia.</li>
<li> Land disputes and discussions about native rights are common, as natives often seek recognition of their land rights and sovereignty.</li>
<li>Native populations may face challenges such as discrimination, loss of land, and socio-economic disparities.</li>
<li>Indigenous rights activists and organizations work to raise awareness and advocate for the rights and well-being of native communities.</li>
</ol>
</font>
</p>
</body>
</html>
```
## c.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Govt.Hospital</title>
</head>
<body bgcolor="violet">
    <h1 align="center">
        <font color="cyan"><b>MANNARGUDI</b></font>
        </h1>
<h3 align="center">
<font color="blue"><b>Government Hospital</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
THE GOVERNMENT HOSPITAL
<ul>
<li>Government hospitals are funded and operated by government authorities, ensuring access to healthcare services for all citizens, regardless of their ability to pay.</li>
<li>They typically offer healthcare services at lower costs, making medical treatment more accessible to the general population.</li>
<li>Government hospitals provide a comprehensive range of medical services, from primary care to specialized treatments and surgeries.</li>
<li>They often act as a safety net for the underserved and uninsured populations, providing vital healthcare services.</li>
</ul>
</font>
</p>
</body>
</html>

```
## d.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Bus Stand</title>
</head>
<body bgcolor="cyan">
    <h1 align="center">
        <font color="purple"><b>MANNARGUDI</b></font>
        </h1>
<h3 align="center">
<font color="blue"><b>Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
    TNSTC Kumbakonam operates a fleet of buses that provide both intracity and intercity transportation services to passengers within the Kumbakonam region.
    The corporation covers a network of routes connecting various towns, villages, and cities in the Kumbakonam area and neighboring regions.
    TNSTC Kumbakonam is a government-run transportation corporation under the Tamil Nadu State Government's authority.
    TNSTC Kumbakonam strives to provide quality customer service to passengers and address their inquiries and concerns.
</b>
</font>
</p>
</body>
</html>


```
## e.html
```

<!DOCTYPE html>
<html lang="en">
<head>
<title>POLICE STATION</title>
</head>
<body bgcolor="yellow">
    <h1 align="center">
        <font color"><b>MANNARGUDI</b></font>
        </h1>

<h3 align="center">
<font color="blue"><b>POLICE</b></font>
</h3>
<hr size="3" color="GREEN">
<p align="justify">
<font face="Tahoma" size="5">
    Police are responsible for enforcing laws, maintaining public order, and protecting citizens from crime and emergencies. Police work to prevent criminal activity through proactive measures like patrolling, community engagement, and public awareness campaigns.Police officers respond to emergency calls, accidents, and incidents, providing assistance and maintaining public safety.
    Police conduct investigations to gather evidence and solve crimes, which can involve interviewing witnesses, collecting physical evidence, and analyzing data.
    The visible presence of police officers can act as a deterrent to criminal behavior in communities.
</font>
</p>
</body>
</html>
```
## OUTPUT
## index.html
![Screenshot 2023-10-31 212413](https://github.com/DEVADARSHAN2/NearMe/assets/119432150/911af919-a4ec-4ea4-91d1-2b10546dc8f5)
## a.html
![Screenshot 2023-10-31 211400](https://github.com/DEVADARSHAN2/NearMe/assets/119432150/e8bdce26-b588-4364-9dc4-e01e760d508c)
## b.html
![Screenshot 2023-10-31 211418](https://github.com/DEVADARSHAN2/NearMe/assets/119432150/88666fef-3eef-4760-a4f8-51f6e3d6a782)
## c.html
![Screenshot 2023-10-31 211436](https://github.com/DEVADARSHAN2/NearMe/assets/119432150/43d6342a-5ccb-4b6c-be1f-18a76cd14125)
## d.html
![Screenshot 2023-10-31 211506](https://github.com/DEVADARSHAN2/NearMe/assets/119432150/7e6e4f09-08f8-4ba1-9b6f-4ded1df2cac3)
## e.html
![Screenshot 2023-10-31 211525](https://github.com/DEVADARSHAN2/NearMe/assets/119432150/a9166ebe-637e-45bc-90dd-87fe2284690a)


## RESULT
The program for implementing image maps using HTML is executed successfully.
