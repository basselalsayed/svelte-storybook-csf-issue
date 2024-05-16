<script lang="ts" context="module">
  import { Story, Template } from "@storybook/addon-svelte-csf";
  import { type Meta } from "@storybook/svelte";
  import Select from "./select.svelte";

  export const meta = {
    title: "UI/Select",
    component: Select<string>,
  } satisfies Meta<Select<string>>;
</script>

<Template let:args>
  <Select {...args} />
</Template>

<Story name="Select Component" />
