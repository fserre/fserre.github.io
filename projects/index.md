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
						<div class="row">
							<div class="col-md-2">
								<img style="max-width: 115px;max-height: 100px; padding: 5px; align:left;" src="{{ p.img }}" />
								<div class="hgroup" >
									<br />
								</div>
							</div>
							<div class="col-md-10"> 
								<div class="hgroup" >  
									<p align="justify">
									{{ p.abstract }}
									</p>
								</div>
							</div>
							
						</div>
						<div class="hgroup">
							<h6>
							{% if p.web %}
							<a href="{{ p.web }}"><span class="current">Web</span></a> |
							{% endif %}
							<a href="{{ p.source }}"><span class="source">Source</span></a>
							{{ p.language }}
							</h6>
						</div>
					</div>
					<!--Divider-->
					<div class="divider-m tCenter margTSmall margBSmall clearfix">
						<div class="col-md-12">
							<div class="zigzag medium clearfix " data-svg-drawing="yes">
								<svg xml:space="preserve" viewBox="0 0 69.172 14.975" width="45" height="5" y="0px" x="0px" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg" version="1.1">
								<path d="M1.357,12.26 10.807,2.81 20.328,12.332 29.781,2.879 39.223,12.321 48.754,2.79 58.286,12.321 67.815,2.793 " style="stroke-dasharray: 93.9851, 93.9851; stroke-dashoffset: 0;"></path>
								</svg>
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

