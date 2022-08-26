---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---
<div style="font-family: 'Source Sans Pro', sans-serif; background: url('/images/banner_no_text.png') no-repeat; background-size: cover; user-select: none;">
	<center>
		<h2 style="font-size: 70px" class="blackpar_title" >🙌 MIRACL </h2>
		<h3 class="blackpar_title">Multilingual Information Retrieval Across a Comprehensive set of Languages</h3>
	</center>
</div>
<br>
<h2 class="blackpar_title" id="overview">Overview</h2>
<p>
We propose a new competition: <b style="font-family: 'Source Sans Pro', sans-serif; font-size: 18px">🙌 MIRACL</b> (Multilingual Information Retrieval Across a Comprehensive set of Languages), which focuses on evaluation of monolingual retrieval systems across a continuum of several diverse languages. These languages have diverse typology, origin, language families and external resource coverage (containing high- and low-resource languages, i.e. languages whose textual web presence and dataset availability is either high or low). 
Prior work and datasets have focused on retrieval in English, shadowing the progress of monolingual retrieval in other languages and multilingual retrieval in multiple languages. 
</p>
<br>
<h2 class="blackpar_title" id="description">Description</h2>
<p>
The goal of our competition is to better evaluate the progress of retrieval systems and help identify limitations across diverse language settings. 
<b style="font-family: 'Source Sans Pro', sans-serif; font-size: 18px">🙌 MIRACL</b> has two tracks: Known-Languages Retrieval and Surprise-Languages Retrieval. We require participants to submit the top-most relevant passages for both tasks. Each participant will be evaluated for retrieval performance measured in terms of accuracy and efficiency. 
To foster training of multilingual systems, we provide the <b style="font-family: 'Source Sans Pro', sans-serif; font-size: 18px">project 🙌 MIRACL</b> dataset: a large balanced monolingual retrieval dataset containing human-annotated data for 18 languages, summing over 300k+ training pairs.
We provide a wide variety of different model architectures as baselines, such as BM25, mDPR, mColBERT and mMonoT5. We hope the competition encourages participants to collaborate and develop systems that are robust, efficient and able to retrieve
information quickly and effectively across a multitude of languages.
</p>
<br/>
<br/>
<h2 class="blackpar_title" id="leaderboard">Leaderboard</h2>
<p>
</p>
<h2 class="blackpar_title" id="submit">Submit</h2>
<p>
<ol>
	<li> Known-Languages Retrieval</li>
	<li> Surprise-Languages Retrieval</li>
</ol>
</p>
<h2 class="blackpar_title" id="organizers">Organizers</h2>
<div class="row_perso">
	<p>
		{% include organizers.html %}
	</p>
</div>
