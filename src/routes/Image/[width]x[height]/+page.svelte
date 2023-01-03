<script lang="ts">
   
   import {page} from '$app/stores'
	import { json } from '@sveltejs/kit';

</script>


<h1>Dimensions</h1>

<pre>
    {JSON.stringify($page, null, 2)}
</pre>