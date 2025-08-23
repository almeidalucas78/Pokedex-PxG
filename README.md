<h1>Pokédex PxG</h1>

<p>Uma <strong>Pokédex para PokéXGames (PxG)</strong> com filtros de <em>tipo</em>, <em>nível</em>, <em>habilidades</em>, <em>busca por nome</em> e <em>ordenação</em>.<br>
O sistema consome um <strong>JSON local</strong> gerado via <strong>web scraping</strong> da wiki do PokéXGames.</p>

<p><a href="https://almeidalucas.dev.br/pokedex-PxG/" target="_blank" rel="noopener noreferrer">👉 Acesse aqui: almeidalucas.dev.br/pokedex-PxG/</a></p>

<h2>🚀 Funcionalidades</h2>
<ul>
  <li>Busca por nome</li>
  <li>Filtros por <strong>Tipo</strong> e <strong>Habilidades</strong></li>
  <li>Filtro por <strong>Nível</strong> (slider duplo + atalhos)</li>
  <li>Ordenação: <em>Dex</em>, <em>Nome</em> e <em>Nível</em></li>
  <li>Contador de resultados + destaque de busca</li>
  <li>Cores por tipo e imagens com fallback</li>
</ul>

<h2>📁 Estrutura</h2>
<pre><code>/
├─ index.html
├─ data/
│  └─ pokexgames_pokemons.json   # gerado via web scraping da wiki PxG
├─ assets/css/style.css
</code></pre>

<h2>📦 Exemplo do JSON</h2>
<pre><code>{
  "dex": 1,
  "name": "Bulbasaur",
  "types": ["Grass", "Poison"],
  "abilities": ["Overgrow", "Chlorophyll"],
  "level": 12,
  "icon": "https://.../bulbasaur.png"
}
</code></pre>

<h2>⚠️ Aviso</h2>
<ul>
  <li>Projeto <strong>não oficial</strong>, sem vínculo com PokéXGames ou The Pokémon Company.</li>
  <li>Dados coletados via <strong>web scraping</strong> da wiki do PokéXGames.</li>
</ul>
