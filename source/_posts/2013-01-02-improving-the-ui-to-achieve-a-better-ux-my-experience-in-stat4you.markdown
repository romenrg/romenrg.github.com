---
layout: post
title: "Improving the UI to achieve a better UX: My experience in Stat4you"
date: 2013-01-02 17:29
comments: true
categories: 
---
<p>I had this article started but uncompleted since September 2012, and as a New Year’s Resolution for 2013 I decided to finish it.</p>

<p>Back then, I had been working for some months as a Front-end engineer in <a href="http://www.stat4you.com">Stat4you</a>. In the early summer we were in a hurry to finish the alpha version of the platform, so we released it without paying too much atention to the details. A feature that was included in this release were the filters for the charts, by means of which users were able to change the positions of the dimensions and also to enable and disable the categories of those dimensions, thus changing the chart being displayed.</p>

<p>The images below are screenshots of the filters initially released in Stat4you:</p>

<img src="http://blog.romenrg.es/images/s4y_table_filter.png" />

<p><em>The image above shows the filters available for the tables in the initial alpha version of the platform. The blue elements represent the containers of the dimensions which, in this case, have been also placed in a particular way to help the user understand the position in which every dimension will appear. The white elements represent the dimensions whilst the orange ones represent the categories of each dimension.</em></p>

<img src="http://blog.romenrg.es/images/s4y_table_filter2.png" />

<p><em>In this image, the categories of one of the dimensions have been unfolded, this way the user can see all the categories available for a particular dimension, not only the previewed ones that can be seen without clicking in the right arrow. Also, it can be seen that the "Periodos" dimension has been moved to fixed (by doing drag and drop). This means that this dimension has been set to a specific category, which by default was the first one.</em></p>

<img src="http://blog.romenrg.es/images/s4y_barAndLine_filter.png" />

<p><em>Finally, there were also filters for the charts. Opposed to the table, in this case all the dimensions were displayed horizontally. The white text over the blue background indicated the position in which the dimension was going to appear if placed there (in the x-axis, in the columns...).</em></p>

<p>As you could guess, this filters were kind of messy for the users. It was a quick design created in a hurry by us (developers) to launch the initial version of the product; so we made the mistake of not taking into account the user experience as much as we should have, although it was a MVP and was going to be improved in the near future.</p>

<p>The days following the launch of the alpha version of Stat4you we had some feedback from visitors, and a portion of the negative feedback was regarding the filters, which appeared to be (as you can guess) confusing and difficult to use, causing a poor user experience. Hence, we decided to improve the user interface to achieve a better acceptance.</p>

<p>To improve the filters we run some usability tests. In my case, I asked for the favor to some friends and family and started the experiment. In this experiment I asked them to access to some datasets within the platform and, once the dataset was accessed, I encouraged them to change the displayed chart or table to achieve a particular visualization (fixing dimensions, disabling some categories of other dimensions and changing their positions). As other users had reported before, the results were poor. It was difficult for them to achieve the changes I requested, but I got tons of information about the improvements needed: such as a search box for the categories, a better indication of the positions in which dimensions could be placed or a visible indication of which was the selected category in the fixed dimensions.</p>

<p>Once these improvements were identified all we had to do was to develop them,knowing that those functionalities were the real needs of the users.</p>

<p>The result of these changes can be seen in the following images:</p>

<img src="http://blog.romenrg.es/images/s4y_table_filter_new.png" />

<p><em>In this first image, the main changes were the labels indicating the positions in which dimensions could be placed and the width of the fixed position box, that now occupied the 100% of the available width.</em></p>

<img src="http://blog.romenrg.es/images/s4y_table_filters2_new.png" />

<p><em>In this case, some changes can be seen: For the fixed dimensions now the selected category is visible at every moment, preventing the users from unfolding the dimension to know which one the selected category is. In addition, a search box has been introduced to search within the categories of a dimension, making it much easier to find a particular category. Moreover, the 'x' that was placed at the top right position of the unfolded box was removed and replaced by an 'accept' button at the bottom right corner. In our experience, this change that forced users to accept the changes in order to close the unfolded categories, helped them to realize that the changes made are always going to be persisted. Before this change was made, some users had the sensation that when the 'x' was clicked, it was going to undo the changes.</em></p>

<img src="http://blog.romenrg.es/images/s4y_barAndLine_filters_new.png" />

<p><em>For the charts, the main change were the labels and shapes of the position boxes. The new interface seems to make the available options of edition easier to understand for users. Besides, it mantains greater uniformity with the tables filters.</em></p>

<p>After these changes, we obtained positive feedback from users, and in the usability tests conducted afterwards, the user experience improved significantly. Firstly we had developed a UI without testing it with real users and when we released the product, the user experience with the filters was poor; we had to conduct some tests once it was in production, detect the problems users were having and then rewrite the interface and re-launch the product with the improved filters.</p>

<p>In conclusion, what I learned back then was something that I already knew, but sometimes with the rush and the misunderstandings of what a MVP actually is, we tend to forget: When designing user interfaces it is really important to prototype first, do some usability testings with the prototype and improve user interfaces by means of users feedback. Then, once these first steps are finished, it is time to implement the tested solution. This way, it will take more time to launch, but it ensures us to achieve a good user experience since the launch day, avoiding the extra time and cost of rebuilding the feature afterwards. It could seem faster to design and implement a simple UI without usability testing and user feedback, but it will have the drawback of causing a worse user experience and, in the long run, it will probably cost more (time and money) in order to rebuild the UI to achieve a better UX.</p>
