<script lang="ts">
	import { CardContainer, Heading2, Hero } from '$lib';
	import PortraitImage from '$lib/assets/portrait1.png';
	import RightArrow from '$lib/assets/right-arrow.svg';

	let cards = [
		{
			title: 'Psychologické poradenství',
			text: 'Konzultace a činnost zaměřena na překonání aktuálních psychických problémů nebo konfliktních situací za pomocí psychologickcýh metod a prostředků.',
			linkText: '',
			linkHref: 'poradenstvi'
		},
		{
			title: 'Koučink',
			text: 'Proces, kterým na základě vhodně a efektivně zvolených otázek kouč provází klienta ke stanovenému cíli.',
			linkText: '',
			linkHref: 'koucink'
		},
		{
			title: 'Psychohygiena',
			text: 'Upevňování duševního zdraví a zvyšování odolnosti klienta vůči široké škále škodlivých vlivů.',
			linkText: '',
			linkHref: 'psychohygiena'
		},
		{
			title: 'Psychodiagnostika',
			text: 'Zjišťování a měření duševních vlastností a stavů dle zadání klienta.',
			linkText: '',
			linkHref: 'psychodiagnostika'
		},
		{
			title: 'Podpůrné skupiny',
			text: 'Praktické metody a techniky pro všední den, přednášky pro školy i jednotlivce.',
			linkText: '',
			linkHref: 'skupiny'
		},
		{
			title: 'Firemní aktivity',
			text: 'Individuálně nastavené balíčky na míru firmám a kolektivům pro podporu a prevenci duševního zdraví zaměstnanců.',
			linkText: '',
			linkHref: 'firmy'
		}
	];
</script>

<Hero
	title="lic. Kristýna Sznapková"
	subtitle="S pokorou pomáhám rozvíjet lidskou duši."
	buttonTitle="Objednejte se"
	imgPath={PortraitImage}
/>
<div class="bg-white rounded-[30px] w-full px-10 py-8 mt-60 mb-44">
	<Heading2>Kdo jsem?</Heading2>
	<div class="flex justify-between text-xdarkgray">
		<p class="w-5/12 text-justify">
			Svou kariéru jsem začala jako vývojář software. Během své cesty jsem vystřídala ohromné
			množství pozic a dlouho jsem nemohla najít takovou, která by mne opravdu bavila a naplňovala.
			Při manařerském postu jsem zjistila, že naslouchání lidem a jejich vedení je mi velmi blízké.
			Díky vzdělávání zaměstnanců jsem se dotkla základů psychologie, které mi naprosto učarovaly, a
			já se rozhodla nastoupit na univerzitu. Postupně jsem se tak propracovala k vývoji lidské
			duše, protože komunikace s lidmi je mi mnohem bližší než komunikace se stroji.
		</p>
		<p class="w-5/12 text-justify">
			Ve své praxi čerpám kromě univerzitních poznatků také ze zkušeností z předchozího pracovního
			poměru. Dále se neustále vzdělávám formou kurzů a workshopů. Díky nekonečnému přísunu nové
			literatury takto obohacuji své obzory o nové techniky, metody a informace. Aktivně se věnuji
			dobrovolnickým aktivitám v oblasti psychologie. Docházím pravidelně na supervize. Lidské
			příběhy jsou jako hvězdy ve vesmíru - každý je jiný a každý je unikátní. Proto ke každému
			klientovi zaujímám individuální přístup plný pokory a respektu.
		</p>
	</div>
	<div class="w-full flex justify-end">
		<a class="text-xdarkgray text-base inline-flex gap-[6px]" href="o-mne"
			>Chci vědět víc<img src={RightArrow} alt="" class="w-5 mt-[4px]" /></a
		>
	</div>
</div>
<CardContainer {cards} />