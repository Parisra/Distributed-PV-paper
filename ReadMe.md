# Code for the paper "Distributed photovoltaics provides key benefits for a highly renewable European energy system"

This repository contains the code notebooks to reproduce the figures in the main text ans supplementary.

## Abstract

In this paper, we aim to redefine the role of distributed solar photovoltaic systems in facilitating the green transition.
Rooftop PV is projected to be a key contributor to future energy landscape, but is often poorly represented in energy models 
due to its distributed nature. It has higher costs compared to utility PV, but offers additional advantages, e.g. 
in terms of social acceptance. We model the European power network with a high spatial resolution of 181 
nodes and a 2-hourly temporal resolution. The modeling of distribution and transmission network allows the 
representation of power distribution losses and differentiates between utility and distributed generation 
and storage. Three scenarios, including a sector-coupled scenario with heating, transport, and industry are 
investigated. The results show that incorporating distributed solar PV leads to total system cost reduction in all scenarios.
Also, underestimating the expenses and losses incurred by the distribution grid seriously undermines the profitability of 
distributed solar PV. The achieved cost reductions (1.4\% for the power sector and 1.9-3.7\% for the sector-coupled scenario)
primarily stem from demand peak reduction because of self-consumption from distributed solar. This reduces the required distribution 
grid capacity and enhances self-sufficiency for countries. The role of distributed PV is noteworthy in the sector-coupled
scenario and is helped by other distributed technologies including heat pumps and electric vehicle batteries.


## Repository Structure

- `notebooks` contains the Jupyter notebooks used for the evaluation of results.
Attention: The code is customised for networks of this study, so care should be taken
when it used to produce similiar figures for PyPSA network files. 

## Usage

The notebooks use pre-solved networks (avialble at zenodo:TBD) to produce the figures from the paper.
PyPSA-Eur-Sec v0.6.0 is used to produce the networks.
 
