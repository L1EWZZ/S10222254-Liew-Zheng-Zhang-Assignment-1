>My intended audience would be business managers or hirers who are looking for people to hire into the working society. The purpose of this website will be to attract job hirers and convince them to hire me for their jobs. This website is catering for job hirers who are looking for people to hire into their jobs. This website is valuable due to all its information about myself and people who are related to me, such as my family members. Their contact information are also allp provided so as to provide some form of communication between my hirer and my family members in case of an event or emergency.

>index.html is the main page which is linked to style.css
>aboutMe.html linked to aboutMe.css is webpage showing information about myself
>contactMe.html linked to contactMe.css is webpage that allow reader to contact me
>family.html linked to family.css is webpage showing information about each family members

>in the aboutMe.js, whenever the radio button is checked, counter starting from 1 will go up by one. but if counter is bigger than 5 (5 pictures in auto slider) then go counter goes back to 1 and show the very first image

>in the family webpage where reader can use arrows to navigate left and right, it basically uses a js script whereby if the arrow is "clicked", machine detects it and -1 +1 to go left and right respectively. But there are some special cases. If we are at first image and user clicks left arrow, machine will make the counter go to 5(5 pictures total) and go the last image. Else do slideLeft function and slide left. If we are at last image and user want to go right, machine will go to the first image, else slide right. Without the 2 ifs, it will not show the first image if user were to be in these 2 scenarios.