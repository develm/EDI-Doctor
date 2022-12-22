<script>
    import { Accordion, AccordionItem } from "carbon-components-svelte";
    import Identifier from "../components/Identifier.svelte";
</script>
  
<Accordion align="start">
  <AccordionItem open>
    <div slot="title">
      <Identifier identifier="R4" />
      <span>Natural Language Classifier</span>
    </div>
    <p>
      Natural Language Classifier uses advanced natural language processing and
      machine learning techniques to create custom classification models. Users
      train their data and the service predicts the appropriate category for the
      inputted text.
    </p>
  </AccordionItem>
  <AccordionItem title="Natural Language Understanding" open>
    <p>
      Analyze text to extract meta-data from content such as concepts, entities,
      emotion, relations, sentiment and more.
    </p>
  </AccordionItem>
  <AccordionItem title="Language Translator" open>
    <p>
      Translate text, documents, and websites from one language to another.
      Create industry or region-specific translations via the service's
      customization capability.
    </p>
  </AccordionItem>
</Accordion>