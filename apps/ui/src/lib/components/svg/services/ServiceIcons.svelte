<script lang="ts">
	export let type: string;
	export let isAbsolute = true;
	import * as Icons from '$lib/components/svg/services';
</script>

{#if type === 'plausibleanalytics'}
	<Icons.PlausibleAnalytics {isAbsolute} />
{:else if type === 'nocodb'}
	<Icons.NocoDb {isAbsolute} />
{:else if type === 'minio'}
	<Icons.MinIo {isAbsolute} />
{:else if type === 'vscodeserver'}
	<Icons.VsCodeServer {isAbsolute} />
{:else if type === 'wordpress'}
	<Icons.Wordpress {isAbsolute} />
{:else if type === 'vaultwarden'}
	<Icons.VaultWarden {isAbsolute} />
{:else if type === 'languagetool'}
	<Icons.LanguageTool {isAbsolute} />
{:else if type === 'n8n'}
	<Icons.N8n {isAbsolute} />
{:else if type === 'uptimekuma'}
	<Icons.UptimeKuma {isAbsolute} />
{:else if type === 'ghost'}
	<Icons.Ghost {isAbsolute} />
{:else if type === 'meilisearch'}
	<Icons.MeiliSearch {isAbsolute} />
{:else if type === 'umami'}
	<Icons.Umami {isAbsolute} />
{:else if type === 'hasura'}
	<Icons.Hasura {isAbsolute} />
{:else if type === 'fider'}
	<Icons.Fider {isAbsolute} />
{:else if type === 'appwrite'}
	<Icons.Appwrite {isAbsolute} />
{:else if type === 'moodle'}
	<Icons.Moodle {isAbsolute} />
{:else if type === 'glitchTip'}
	<Icons.GlitchTip {isAbsolute} />
{:else if type === 'searxng'}
	<Icons.Searxng {isAbsolute} />
{:else if type === 'weblate'}
	<Icons.Weblate {isAbsolute} />
{:else if type === 'grafana'}
	<Icons.Grafana {isAbsolute} />
{:else if type === 'trilium'}
	<Icons.Trilium {isAbsolute} />
{/if}
