---
layout: page
title: Rollen en Governance Patronen
description: Overzicht van alle rollen en organisatiemodellen in het open source ecosysteem
---

# Rollen en Governance Patronen

Deze pagina biedt een overzicht van alle rollen en governance modellen die voorkomen in een open source ecosysteem voor overheids-software. Het dient als een naslagwerk en woordenboek voor implementatie.

## Ecosysteem Rollen

{% assign role_categories = site.data.ecosystem_roles.development_roles | concat: site.data.ecosystem_roles.infrastructure_roles | concat: site.data.ecosystem_roles.quality_assurance_roles | concat: site.data.ecosystem_roles.management_support_roles | concat: site.data.ecosystem_roles.coordination_roles | concat: site.data.ecosystem_roles.research_innovation_roles | group_by: 'category' %}

{% for category_group in role_categories %}
### {{ category_group.name }}

<div class="role-cards">
{% for role in category_group.items %}
  <div class="role-card">
    <h4 class="role-name">{{ role.name }}</h4>
    <p class="role-description">{{ role.description }}</p>
    
    <div class="role-details">
      <div class="role-section">
        <h5>Verantwoordelijkheden</h5>
        <ul class="role-responsibilities">
        {% for responsibility in role.responsibilities %}
          <li>{{ responsibility }}</li>
        {% endfor %}
        </ul>
      </div>
      
      {% if role.skills_required %}
      <div class="role-section">
        <h5>Vereiste vaardigheden</h5>
        <div class="role-skills">
        {% for skill in role.skills_required %}
          <span class="skill-tag">{{ skill }}</span>
        {% endfor %}
        </div>
      </div>
      {% endif %}
      
      {% if role.examples %}
      <div class="role-section">
        <h5>Voorbeelden</h5>
        <ul class="role-examples">
        {% for example in role.examples %}
          <li>{{ example }}</li>
        {% endfor %}
        </ul>
      </div>
      {% endif %}
    </div>
  </div>
{% endfor %}
</div>
{% endfor %}

---

## Governance Modellen

De governance modellen zijn georganiseerd in drie hoofdcategorieën: interne modellen, externe modellen, en collectieve modellen.

### Interne Modellen
*Modellen waarbij de organisatie zelf de software en infrastructuur beheert*

<div class="governance-models">
{% for model in site.data.ecosystem_roles.governance_models.internal %}
  <div class="governance-card internal">
    <h4 class="model-name">{{ model.name }}</h4>
    <p class="model-description">{{ model.description }}</p>
    
    <div class="model-details">
      <div class="pros-cons">
        <div class="pros">
          <h5>Voordelen</h5>
          <ul>
          {% for advantage in model.advantages %}
            <li>{{ advantage }}</li>
          {% endfor %}
          </ul>
        </div>
        
        <div class="cons">
          <h5>Nadelen</h5>
          <ul>
          {% for disadvantage in model.disadvantages %}
            <li>{{ disadvantage }}</li>
          {% endfor %}
          </ul>
        </div>
      </div>
      
      {% if model.examples %}
      <div class="model-examples">
        <h5>Voorbeelden</h5>
        <ul>
        {% for example in model.examples %}
          <li>{{ example }}</li>
        {% endfor %}
        </ul>
      </div>
      {% endif %}
    </div>
  </div>
{% endfor %}
</div>

### Externe Modellen
*Modellen waarbij externe partijen de software en infrastructuur beheren*

<div class="governance-models">
{% for model in site.data.ecosystem_roles.governance_models.external %}
  <div class="governance-card external">
    <h4 class="model-name">{{ model.name }}</h4>
    <p class="model-description">{{ model.description }}</p>
    
    <div class="model-details">
      <div class="pros-cons">
        <div class="pros">
          <h5>Voordelen</h5>
          <ul>
          {% for advantage in model.advantages %}
            <li>{{ advantage }}</li>
          {% endfor %}
          </ul>
        </div>
        
        <div class="cons">
          <h5>Nadelen</h5>
          <ul>
          {% for disadvantage in model.disadvantages %}
            <li>{{ disadvantage }}</li>
          {% endfor %}
          </ul>
        </div>
      </div>
      
      {% if model.requirements %}
      <div class="model-requirements">
        <h5>Vereisten</h5>
        <ul>
        {% for requirement in model.requirements %}
          <li>{{ requirement }}</li>
        {% endfor %}
        </ul>
      </div>
      {% endif %}
      
      {% if model.considerations %}
      <div class="model-considerations">
        <h5>Overwegingen</h5>
        <ul>
        {% for consideration in model.considerations %}
          <li>{{ consideration }}</li>
        {% endfor %}
        </ul>
      </div>
      {% endif %}
    </div>
  </div>
{% endfor %}
</div>

### Collectieve Modellen
*Modellen waarbij meerdere partijen gezamenlijk eigenaarschap en beheer delen*

<div class="governance-models">
{% for model in site.data.ecosystem_roles.governance_models.collective %}
  <div class="governance-card collective">
    <h4 class="model-name">{{ model.name }}</h4>
    <p class="model-description">{{ model.description }}</p>
    
    <div class="model-details">
      <div class="pros-cons">
        <div class="pros">
          <h5>Voordelen</h5>
          <ul>
          {% for advantage in model.advantages %}
            <li>{{ advantage }}</li>
          {% endfor %}
          </ul>
        </div>
        
        <div class="cons">
          <h5>Nadelen</h5>
          <ul>
          {% for disadvantage in model.disadvantages %}
            <li>{{ disadvantage }}</li>
          {% endfor %}
          </ul>
        </div>
      </div>
      
      {% if model.examples %}
      <div class="model-examples">
        <h5>Voorbeelden</h5>
        <ul>
        {% for example in model.examples %}
          <li>{{ example }}</li>
        {% endfor %}
        </ul>
      </div>
      {% endif %}
    </div>
  </div>
{% endfor %}
</div>

---

## Hoe deze pagina te gebruiken

- **Voor project managers**: Gebruik de rollen sectie om teams samen te stellen
- **Voor beleidsmakers**: Bekijk de governance modellen om de beste organisatievorm te kiezen
- **Voor implementatieconsultants**: Gebruik als checklist voor volledige ecosysteem opzet
- **Voor gemeenten**: Vergelijk verschillende modellen om te bepalen wat past bij jullie situatie

*Deze pagina wordt automatisch gegenereerd uit de gestructureerde data in `_data/ecosystem_roles.yml`.*