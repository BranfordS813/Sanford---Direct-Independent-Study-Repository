
The project needs to deal with big data. The question then is what to do with it. And are there other data to incorporate as well? But more so, what is the purpose of the data? Is it for Classification? Prediction?

The most important thing is data. Try to see if there is data that exists, especially public domain data and lots of it. Then do the topic project. **AND READ WHATEVER PAPERS THAT COME WITH THE DATASET BEFORE MAKING A DECLARATIVE PROJECT.**

<span style="color: red;">It's important to make sure that data is provided and that you know and understand the data. </span>

This is a datamining project, even if deciding between a classical machine learning approach or deep learning.

### Topic Overview

This project focuses on examining overlaps between the fields of bioinformatics and new urbanism. In short, bioinformatics focuses on biological/medical data related to an organism(s) along with use in medicine, medical science, and clinical studies; new urbanism deals with improving the state and quality of urban environments besides relying on sprawl and car dependency as well as looking into how urban environments can have an impact on health, safety, and even mental health; especially when differentiating between walkable and dense urban areas vs sprawled and car dependent areas.

As such, there are a few key ways that bioinformatics and new urbanism can overlap 

 Health related information mapped to spatial information, such as incidence of disease or illness based on where people leave - sparse vs dense. The issue with this is that it leads to predictable results where car centric areas will obviously have more incidences of health problems compared to dense urban areas whereupon walking is encouraged. As such, it may be necessary to examine more specific and nuanced topics, like exploring information on 'how' or even the mechanicals of 'why' a disease may spread faster (or slower) based on the location between sprawled and dense towns and cities. **Still, it is important to know that Bioinformatics focuses on the information related to biological entities as well as medical applications, like disease classification, genetic sequencing and archiving, drug targeting, personalized medicine, etc.** 

Another basic overlap is that of information (or in this case, informatics). Biology is filled with a plethora of traditional databases based on several different Omics, especially regarding 

- Genomics (DNA)
- Transcriptomics (RNA)
- Proteomics (Proteins)
- Metabolomics (Metabolites and Macro Molecules) . 
![[metabolomics-figure-1024x576.webp]]
But with new urbanism, information is usually associated with informatics regarding physical space, population statistics, planning, and design. Specifically, community informatics and urban informatics. **One key thing to understand about New Urbanism is that it is based on community planning through participatory means - rather than purely bureaucratic which can include direct involvement from members who live in the community and small business and firms focused on new urbanism principles as opposed to more large corporate entities - and creating town/city design with a humanist approach, specifically making areas more livable, accessible, and promoting human wellness, especially when building around a human-scale.** With this comes a priority for new urban planners to construe more accessible forms of living and transit that is not dominated by cars and car dependency (i.e., car centricity). This includes other topics like:

- Curbing suburban sprawl
- Construction of massive infrastructure which destroys natural environments, neighborhoods, and downtown areas
- Decreasing sessile life styles that cause health problems due to sprawled areas and car dependency
- Encouraging walkability and more green spaces
- Improving the sense of community for a city/town by incorporating 3rd spaces and promoting morale boosting aesthetics (like parks, public gathering spaces, and preserving cultural/historical landmarks)
- Preventing and amending duplicitous urban design, especially made deliberately by car focused traffic engineers and traditional urban planners focusing on sprawl
- Countering established laws and mandates that counter spawl and mid century urban design like eliminating parking minimums (and encouraging parking maximums) as well as encouraging mixed used zoning (instead of single use zoning) and inclusive housing
- Reducing the cost of unnecessary car dependency, especially when it costs more for municipalities to build and maintain infrastructure for cars as opposed to not being overly reliant on them
- Reducing the atomization of society caused by sprawl; and promoting more open space and perseveration of natural environments, parks, natural habitats, forests, and important rural areas like cultural heritage sites and farmland.
- Utilizing urban planning, urban design, and civil engineering to better design streets and roads for more holistic and inclusive use that does not prioritize cars. This includes reducing speeds, adding more accessibility options for those who cannot drive, and adding alternative forms of transit without being encumbered by cars, such as single lane buses and transit oriented development that does not require a car to get to.

==This sentence is highlighted in yellow,== 

### Venn Diagram

The following is a Venn Diagram comparing and contrasting a sample of Bioinformatics vs New Urbanism subjects and where potential overlap could occur between the two.

Venn Diagram (Interweave)

```interweave
- sets:
   - Bioinformatics
  labels: 
   - "Bioinformatics"
   - ". Sequencing"
  size: 30
  color: "#3B826"
  opacity: 0.5
  
- sets: 
   - New Urbanism
  labels: 
   - "New Urbanism"
   - ". Walkability" 
  size: 30
  color: "10B981"
  opacity: 0.5
  
- sets: 
   - Bioinformatics
   - New Urbanism 
  labels: 
   - "Urban Metagenomics"
  size: 3
  color: "#8B5CF6"
  opacity: 0.7
```


```interweave
- sets:
    - Bioinformatics
  labels:
    - Bioinformatics
    - ". High-Throughput Sequencing"
    - ". Metagenomic Profiling"
  size: 10
  color: "#3B82F6"
  opacity: 0.5
  
- sets:
    - New Urbanism
  labels:
    - New Urbanism 
    - ". Walkability"
    - ". Transit-Oriented Development"
  size: 10
  color: "#10B981"
```

Interweave appears not to be working

Venn Diagram (mermaid)

```mermaid
graph LR
	subgraph S1["Bioinformatics"]
		A1[". High-Throughput Sequencing"]
		A2[". Metagenomic Profiling"]
	end
	
	subgraph S2["OVERLAP: Urban Metagenomics"]
		M1[". Built-Enviornment Microbes"]
		M2[". Antimicrobial Resistance Tracking"]
	end 
	
	subgraph S3["New Urbanism"]
		B1[". Walkabilty"]
		B2[". Transit-Oriented Devlopment"]
	end
	
	S1 --- S2
	S2 --- S3
```



Venn Diagram - HTML

<div style="display: flex; gap: 10px; text-align: left; margin-top: 10px;">
  <div style="flex: 1; background: rgba(59, 130, 246, 0.15); padding: 15px; border-radius: 8px; border: 1px solid #3B82F6;">
    <h4 style="margin-top:0; color: #3B82F6;">Bioinformatics</h4>
    <ul>
      <li>High-Throughput Sequencing</li>
      <li>Metagenomic Profiling</li>
    </ul>
  </div>
  <div style="flex: 1; background: rgba(139, 92, 246, 0.15); padding: 15px; border-radius: 8px; border: 1px solid #8B5CF6;">
    <h4 style="margin-top:0; color: #8B5CF6;">Urban Metagenomics (Overlap)</h4>
    <ul>
      <li>Built-Environment Microbes</li>
      <li>Spatial Microbiome Analysis</li>
    </ul>
  </div>
  <div style="flex: 1; background: rgba(16, 185, 129, 0.15); padding: 15px; border-radius: 8px; border: 1px solid #10B981;">
    <h4 style="margin-top:0; color: #10B981;">New Urbanism</h4>
    <ul>
      <li>Walkability</li>
      <li>Transit-Oriented Development</li>
    </ul>
  </div>
</div>

Venn Diagram - Matplotlib-Venn 

![[Pasted image 20260908225720.png]]




