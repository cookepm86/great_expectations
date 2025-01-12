import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import TechnicalTag from '@site/docs/term_tags/_tag.mdx';

Get an environment to run the code in this guide. Please choose an option below.

<Tabs
  groupId="yaml-or-python"
  defaultValue='yaml'
  values={[
  {label: 'No CLI + filesystem', value:'yaml'},
  {label: 'No CLI + no filesystem', value:'python'},
  ]}>

 <TabItem value="yaml">

If you use Great Expectations in an environment that has filesystem access, and prefer not to use the <TechnicalTag tag="cli" text="CLI" />, run the code in this guide in a notebook or other Python script.

</TabItem>
<TabItem value="python">

If you use Great Expectations in an environment that has no filesystem (such as Databricks or AWS EMR), run the code in this guide in that system's preferred way.

</TabItem>

</Tabs>
