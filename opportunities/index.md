---
layout: default
title: Solicitations
permalink: /opportunities/
published: true
---
# Solicitations
We oversee commodity and service procurements for Aviation, Parks, Watershed, Public Works, and General Fund departments. Use the search tool below to view current and archived bid opportunities, download bid documents, and sign up for future updates.

<script type="text/javascript">
  $(function() {
      $('#project-criteria').change(function() {
        $('#project-departments').fadeIn();
      });

      $('#project-departments').change(function() {
        console.log("YOOO..");
        $('#plan_holder_project_id').fadeIn();
      });

      $('#plan_holder_project_id').change(function() {
        console.log("CHANGES!");
        if($(this).val() != "") {
          $('#project-info-well').fadeIn();
          $('#project-info-project-number').html("adsfasdf");
          $('#project-info-project-name').html("adfasdd");
          $('#bidder-fodder').html("");
          $('#bidder-fodder-list').remove();
          console.log("UO!")
          //initialize_map(, );
        } else {
          $('#project-info-well').fadeOut();
        }
      });
    });
</script>
<div class="form-group">
  <div class="row">
    <div class="col-md-8">
      <p>
        <strong><span style="color: #c7254e; font-weight: bold;"> *</span> denotes required fields</strong><br>
      </p>
      <label for="plan_holder_Select a bid opportunity">Select the criteria you want to use to search for bids:</label><br />
      <select class="form-control input-lg" id="project-criteria" name="plan_holder[criteria]">
        <option value="due-date">Browse by due date</option>
        <option value="department">Browse by department</option>
      </select><br /><br />

      <select class="form-control input-lg" id="project-departments" style="display: none;" name="plan_holder[criteria]">
        <option value="due-date">Aviation</option>
        <option value="department">Corrections</option>
        <option value="department">Finance</option>
        <option value="department">Fire</option>
        <option value="department">Human Resources</option>
        <option value="department">Information Technology</option>
        <option value="department">Law</option>
        <option value="department">Parks & Recreation</option>
        <option value="department">Planning & Community Development</option>
        <option value="department">Procurement</option>
        <option value="department">Police</option>
        <option value="department">Public Works</option>
        <option value="department">Watershed Management</option>
      </select><br /><br />

      <label for="plan_holder_Select a bid opportunity" style="display:none;">Select a bid opportunity</label>
      <span style="color: #c7254e; font-weight: bold; display: none;"> *</span><br>
      <select class="form-control input-lg" style="display: none;" id="plan_holder_project_id" name="plan_holder[project_id]">
        <option value=""></option>
        <option value="66">00-00000 - Superbly Awesome Project</option>
        <option value="6">6856-AP - 2014 DEBRIS REMOVAL EQUIPMENT</option>
        <option value="1">7108-AP - OIL, GREASE, AND TRANSMISSI...</option>
        <option value="5">7174-MT - CRUSHED STONE RIP-RAP</option>
        <option value="7">7188-PL - RENTAL OF HYDRAULIC SUBMERS...</option>
        <option value="8">7191-PL - SERVICE AND REPAIR OF EMERG...</option>
        <option value="17">7226-AP - VARIABLE SPEED DRIVES AND L...</option>
        <option value="9">7240-AP - VARIOUS DIESEL REFUSE TRUCKS</option>
        <option value="10">7243-PD - AIR EMISSION SOURCE/UINIT T...</option>
        <option value="11">7245-AP - REPAIR PARTS &amp;amp; SERVICE FOR ...</option>
        <option value="20">7266-PL - THE RENTAL OF UNIFORMS FOR ...</option>
        <option value="12">7268-PL - GAS MONITORS, SENSORS, SUPP...</option>
        <option value="22">7274-PL - MSA 5200 EVOLUTION THERMAL ...</option>
        <option value="3">7275-PL - TENT RENTAL FOR PARKS, RECR...</option>
        <option value="13">7276-PL - WASTE OIL REMOVAL AND RECOVERY</option>
        <option value="4">7277-PL - PROCESS CONTROL EQUIPMENT </option>
        <option value="2">7279-PL - ELECTRIC LAMPS</option>
        <option value="21">7298-AP - RENTAL OF TRENCH SAFETY BOX...</option>
        <option value="15">7303-PL - VARIOUS LUBRICANTS FOR EQUI...</option>
        <option value="16">7306-AP - CONSTRUCTION EQUIPMENT</option>
        <option value="18">7312-MT - COLD MIX ASPHALTIC CONCRETE </option>
        <option value="19">7346-AP - ASPHALT REPAIR EQUIPMENT</option>
        <option value="49">FC-6770 - Zoning Ordinance Rewrite As...</option>
        <option value="37">FC-6784 - Urban Forestry </option>
        <option value="27">FC-6831 - East Atlanta Water Main Rep...</option>
        <option value="40">FC-6836 - Citywide Managing General C...</option>
        <option value="30">FC-6997 - Design/Builld of Southeast ...</option>
        <option value="25">FC-7092  - Annual Contract for Centrif...</option>
        <option value="34">FC-7093 - Annual Contract for Electri...</option>
        <option value="23">FC-7095 - Auto Physical Damage Apprai...</option>

      </select>
    </div>
  </div><br>
  <div class="row" id="project-info-well" style="display: none;">
    <div class="col-md-8">
      <div class="well" id="project-info-well-content">
        <strong style="font-size: 12pt;">Superbly Awesome Project (FC-00-00000)</strong>
        <hr style="border-color: #ccc;" />
        <p>
          <strong>Project summary</strong><br />
          ro eget nunc posuere blandit eu sit amet erat. Proin facilisis pellentesque pretium. Sed convallis rutrum turpis vel blandit. Donec id rhoncus diam. Duis ac bibendum est, in fringilla erat. Aliquam congue, risus in accumsan pulvinar, sapien nisi posuere velit, a pharetra lectus tellus egestas sapie
        </p>
        <p>
          <strong>Bids due</strong><br />
          1:59pm EST, Tuesday, September 30th, 2014
        </p>
        <p>
          <strong>Site visit information</strong><br />
          1:30pm EST, Thursday, September 18, 2014<br />
          55 Trinity Ave SW, Atlanta, GA 30303<br /><br />
          <img src="http://maps.googleapis.com/maps/api/staticmap?center=55+Trinity+Ave+SW,Atlanta,GA&zoom=15&size=900x200&markers=color:red%7C33.748460200000004,-84.39067779999999" style="border: 1px solid #ccc;"/>
        </p>
        <div>
          <a href="/atlanta-procurement-www/opportunities/fc-7252" class="btn btn-success">Get more information</a>
        </div>
      </div>
    </div>
  </div>
</div>
