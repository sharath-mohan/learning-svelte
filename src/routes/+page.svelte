<script>
	import DynamicAttributes from '../chapters/introduction/DynamicAttributes.svelte';
	import AddingData from '../chapters/introduction/AddingData.svelte';
	import Styling from '../chapters/introduction/Styling.svelte';
	import NestedComponents from '../chapters/introduction/NestedComponents.svelte';
	import HtmLtags from '../chapters/introduction/HTMLtags.svelte';
	import Statements from '../chapters/reactivity/Statements.svelte';
	import Declarations from '../chapters/reactivity/Declarations.svelte';
	import UpdatingArrayAndObject from '../chapters/reactivity/UpdatingArrayAndObject.svelte';
	import DeclaringProps from '../chapters/props/DeclaringProps.svelte';
	import DefaultValueProps from '../chapters/props/DefaultValueProps.svelte';
	import SpreadProps from '../chapters/props/SpreadProps.svelte';
	import IfBlocks from '../chapters/logic/IfBlocks.svelte';
	import IfElseBlocks from '../chapters/logic/IfElseBlocks.svelte';
	import IfElseifElseBlocks from '../chapters/logic/IfElseifElseBlocks.svelte';
	import EachBlocks from '../chapters/logic/EachBlocks.svelte';
	import KeyedEachBlock from '../chapters/logic/KeyedEachBlock.svelte';
	import DomEvents from '../chapters/events/DOMEvents.svelte';
	import InlineEvents from '../chapters/events/InlineEvents.svelte';
	import EventModifiers from '../chapters/events/EventModifiers.svelte';
	import ComponentEvents from '../chapters/events/ComponentEvents.svelte';
	import DomEventsForwarding from '../chapters/events/DOMEventsForwarding.svelte';
	import TextInput from '../chapters/bindings/TextInput.svelte';
	import TextArea from '../chapters/bindings/TextArea.svelte';
	import SingleCheckBox from '../chapters/bindings/SingleCheckBox.svelte';
	import Select from '../chapters/bindings/Select.svelte';
	import OnMountCycle from '../chapters/lifecycle/OnMountCycle.svelte';
	const props = {
		framework: 'svelte',
		basedon: 'compiler technology'
	};
</script>

<h1>learnings from svelte tutorials</h1>
<AddingData />
<DynamicAttributes />
<Styling />
<NestedComponents />
<HtmLtags />
<Statements />
<Declarations />
<UpdatingArrayAndObject />
<DeclaringProps propsData="data passed from parents" />
<DefaultValueProps />
<SpreadProps {...props} />
<IfBlocks />
<IfElseBlocks />
<IfElseifElseBlocks />
<EachBlocks />
<KeyedEachBlock />
<DomEvents />
<InlineEvents />
<EventModifiers />
<ComponentEvents />
<DomEventsForwarding />
<TextInput />
<TextArea />
<SingleCheckBox />
<Select />
<OnMountCycle />
