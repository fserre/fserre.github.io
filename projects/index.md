---
layout: page
title: Projects
---


<div class="block-content ">
	<div class="timeline education">
		{% for p in site.pages %}
		{% if p.type == 'project' %}
		<div class="row ">
			<div class="col-md-12">
				<div class="exp-holder">
					<div class="exp">
						<div class="hgroup" >
							<h4>{{ p.title }}</h4>
						</div>
						<div class="">
							<div class="col-md-5" style="padding:0px">
								<img style="max-width: 300px;max-height: 100px;" src="{{ p.img }}" />
								<div class="hgroup" >
        							<div class="h6">
                                        {% if p.web %}
                                            <a href="{{ p.web }}"><span class="source">Web</span></a> |
                                        {% endif %}
                                        <a href="{{ p.source }}"><span class="source">Source</span></a>
                                    </div>
								</div>
							</div>
							<div class="col-md-7"> 
								<div class="hgroup" >  
									<p align="justify">
									{{ p.abstract }}
									</p>
								</div>
							</div>
						</div>
					</div>
				</div>
				<!--End experience holder-->
			</div>
		</div>
		{% endif %}
		{% endfor %}
	</div>
</div>

