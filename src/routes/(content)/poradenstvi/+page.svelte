<script>
	import { Anchor, List, Paragraph } from '$lib';
	import PoradenstviImg from '$lib/assets/poradenstvi.jpg';
	import { titleStore } from '../store';
	titleStore.set('Psychologické poradenství');
</script>

<Paragraph>
	Psychologické poradenství je konzultace a činnost zaměřena na překonání aktuálních psychických
	problémů klientů nebo konfliktních situací za pomocí psychologickcýh metod a prostředků. Může se
	jednat o oblast kariéry (volba a změna povolání), rodiny, manželských a partnerských vztahů,
	školní a výchovnou nebo o oblast vztahu k sobě sama a rozvoje osobnosti.
</Paragraph>

<div class="flex flex-col xl:flex-row xl:items-center gap-10 xl:gap-36">
	<div class="">
		<Paragraph><span class="font-bold">Co konkrétně do této oblasti může patřit?</span></Paragraph>
		<List>
			<li>aktuální výskyt úzkostí před zkouškou nebo prezentací</li>
			<li>přístup k problémům dětí</li>
			<li>příprava na roli rodiče nebo prarodiče</li>
			<li>těžká rozhodnutí a složité životní křižovatky</li>
			<li>volba výchovného stylu</li>
			<li>adaptace na situaci odchodu do důchodu</li>
			<li>volba vysoké školy</li>
			<li>změna povolání v produktivním věku</li>
			<li>pracovní zátěž a stres</li>
			<li>konfliktní situace</li>
			<li>otázky sebehodnoty a spirituality</li>
			<li>budování komunikačních dovedností</li>
			<li>seberozvojová témata (např. rozvíjení soft skills)</li>
			<li>ujasňování a hledání identity</li>
			<li>doprovázení na cestě za změnou pohlaví</li>
		</List>
	</div>
	<div class="w-1/2 self-center xl:w-1/3">
		<img src={PoradenstviImg} alt="Ilustracni obrazek" class="object-contain mx-auto" />
	</div>
</div>
<Paragraph>
	Moje cílová skupina jsou dospělí lidé. Pracuji tedy s klienty, kteří již dosáhli plnoletosti.
	Výjimky pouze ve velice akutních případech po telefonické domluvě předem.
</Paragraph>

<Paragraph>
	Nevěnuji se rodinné a partnerské sféře, nepracuji s dětmi a s osobami se závažnými psychickými
	poruchami. Pracuji vždy pouze s jednotlivci.
</Paragraph>

<Paragraph>
	Ceník, podmínky a další informace naleznete <Anchor href="cenik">ZDE.</Anchor>
</Paragraph>
