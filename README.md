# UFOs

## Project Overview
This project focuses on building a dynamic webpage that accepts user inputs and adjusts accordingly to display information about UFO sightings. In order to perform analysis, users filter the UFO sightings table based on multiple criteria such as the event date, city, state, country and shape. 

## Results

### Search Criteria Procedure

#### Index page
This is the initial page. The user can re-initialize the page by clicking on the navigation bar at the top.

![image](https://user-images.githubusercontent.com/111802162/203190666-11116e38-afc7-4fb5-8fc3-2056acfc171b.png)

#### Filtering by event date
The user enters the desired date, the change is detected and the table is updated accordingly.

![image](https://user-images.githubusercontent.com/111802162/203191086-5d83ffb2-7aed-4400-a589-578d01907324.png)

#### Filtering by city
The user enters the desired city, the change is detected and the table is updated accordingly.

![image](https://user-images.githubusercontent.com/111802162/203191479-ae056256-ade1-4081-959f-24974a531388.png)

#### Filtering by state
The user enters the desired state, the changes are detected and the table is updated accordingly.

![image](https://user-images.githubusercontent.com/111802162/203191389-57d1bc99-a593-43c7-9ef6-9bd109cce6df.png)

All filter parameters can be entered simultaneously.
<br>

## Summary
- One drawback of this design is the difficulty for the user to know what parameter to use for the filtering. For example to pick a city, the user would have to go through the table a find the city desired for the analysis.
- A way to address this would be to present drop-down lists including all filter values in place of the input fields.<br>
Each list would need to update after a parameter is selected in any filter.
- Including a button to clear the filters is also needed. The button would be located below the last filter.
