<script>
  import { browser } from "$app/environment";
  import { ChartComponent as Chart, TraceList } from "libchartium";
</script>

{#if browser}
  <Chart traces={TraceList.empty()} />
{/if}
