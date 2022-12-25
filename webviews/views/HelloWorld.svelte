<script>
    import { Accordion, AccordionItem } from "carbon-components-svelte";
    import Identifier from "../components/Identifier.svelte";
</script>

<style lang="scss">
  div {
    color: #cccccc;
    font-size: 12px;
  }

  .identifier {
    font-size: 14px;
  }

  .row {
    border-bottom: 1px solid #3f3d3d;
    padding: 5px;
  }

  *[class*="row"]:hover {
    background-color: rgb(82, 80, 80);
  }
</style>
  
<Accordion align="start">
  <AccordionItem open>
    <div slot="title" class="idnetifier">
      <Identifier identifier="B4" />
      <span>Beginning Segment for Inquiry or Reply</span>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">Shipment Status Code</div>
      <div class="col-md-8 col-xs-6">Return Container</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">Date</div>
      <div class="col-md-8 col-xs-6">Jan 4, 2022 / 7:27:00 AM</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">CMCU</div>
      <div class="col-md-8 col-xs-6">5564924</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">Equipment Status Code</div>
      <div class="col-md-8 col-xs-6">Empty</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">Equipment Type</div>
      <div class="col-md-8 col-xs-6">45R0</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">United Nations Location Code (UNLOCODE)</div>
      <div class="col-md-8 col-xs-6">PRSJU</div>
    </div>
  </AccordionItem>
  <AccordionItem open>
    <div slot="title" class="identifier">
      <Identifier identifier="B4" />
      <span>Beginning Segment for Inquiry or Reply</span>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">Shipment Status Code</div>
      <div class="col-md-8 col-xs-6">Return Container</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">Date</div>
      <div class="col-md-8 col-xs-6">Jan 4, 2022 / 7:27:00 AM</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">CMCU</div>
      <div class="col-md-8 col-xs-6">5564924</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">Equipment Status Code</div>
      <div class="col-md-8 col-xs-6">Empty</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">Equipment Type</div>
      <div class="col-md-8 col-xs-6">45R0</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">United Nations Location Code (UNLOCODE)</div>
      <div class="col-md-8 col-xs-6">PRSJU</div>
    </div>
  </AccordionItem>
  <AccordionItem open>
    <div slot="title" class="identifier">
      <Identifier identifier="B4" />
      <span>Beginning Segment for Inquiry or Reply</span>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">Shipment Status Code</div>
      <div class="col-md-8 col-xs-6">Return Container</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">Date</div>
      <div class="col-md-8 col-xs-6">Jan 4, 2022 / 7:27:00 AM</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">CMCU</div>
      <div class="col-md-8 col-xs-6">5564924</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">Equipment Status Code</div>
      <div class="col-md-8 col-xs-6">Empty</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">Equipment Type</div>
      <div class="col-md-8 col-xs-6">45R0</div>
    </div>
    <div class="row">
      <div class="col-md-4 col-xs-6">United Nations Location Code (UNLOCODE)</div>
      <div class="col-md-8 col-xs-6">PRSJU</div>
    </div>
  </AccordionItem>
</Accordion>