<script lang="ts">
	import { CardContainer, Heading2, Hero, Anchor, TextLink } from '$lib';
	import PortraitImage from '$lib/assets/portrait1.png';
	import PortalLogo from '$lib/assets/portal.png';
	import PaspartaLogo from '$lib/assets/pasparta.png';

	let cards = [
		{
			title: 'Psychologické poradenství',
			text: 'Konzultace a činnost zaměřena na překonání aktuálních psychických problémů nebo konfliktních situací za pomocí psychologickcýh metod a prostředků.',
			linkText: '',
			linkHref: `poradenstvi`
		},
		{
			title: 'Koučink',
			text: 'Proces, kterým na základě vhodně a efektivně zvolených otázek kouč provází klienta ke stanovenému cíli.',
			linkText: '',
			linkHref: `koucink`
		},
		{
			title: 'Psychohygiena',
			text: 'Upevňování duševního zdraví a zvyšování odolnosti klienta vůči široké škále škodlivých vlivů.',
			linkText: '',
			linkHref: `psychohygiena`
		},
		{
			title: 'Psychodiagnostika',
			text: 'Zjišťování a měření duševních vlastností a stavů dle zadání klienta.',
			linkText: '',
			linkHref: `psychodiagnostika`
		},
		{
			title: 'Podpůrné skupiny',
			text: 'Praktické metody a techniky pro všední den, přednášky pro školy i jednotlivce.',
			linkText: '',
			linkHref: `skupiny`
		},
		{
			title: 'Firemní aktivity',
			text: 'Individuálně nastavené balíčky na míru firmám a kolektivům pro podporu a prevenci duševního zdraví zaměstnanců.',
			linkText: '',
			linkHref: `firmy`
		}
	];
</script>

<svelte:head>
	<title>PSOVA - Psychologické poradenství a koučink Ostrava</title>
</svelte:head>

<Hero
	title="Kristýna Sznapková"
	subtitle="S pokorou pomáhám rozvíjet lidskou duši."
	buttonTitle="Objednejte se"
	imgPath={PortraitImage}
/>
<div class="bg-white rounded-[30px] w-full px-10 py-8 mt-60 mb-28">
	<Heading2>Kdo jsem?</Heading2>
	<div class="xl:flex justify-between text-xdarkgray">
		<p class="xl:w-5/12 text-justify xl:leading-relaxed">
			Svou kariéru jsem začala jako vývojář software. Během své cesty jsem vystřídala ohromné
			množství pozic a dlouho jsem nemohla najít takovou, která by mne opravdu bavila a naplňovala.
			Při manažerském postu jsem zjistila, že naslouchání lidem a jejich vedení je mi velmi blízké.
			Díky vzdělávání zaměstnanců jsem se dotkla základů psychologie, které mi naprosto učarovaly, a
			já se rozhodla nastoupit na univerzitu. Postupně jsem se tak propracovala k vývoji lidské
			duše, protože komunikace s lidmi je mi mnohem bližší než komunikace se stroji. Lidské příběhy
			jsou jako hvězdy ve vesmíru - každá je jiná a každá je unikátní.
		</p>
		<p class="xl:w-5/12 mt-3 xl:mt-0 text-justify xl:leading-relaxed">
			Proto ke každému klientovi zaujímám individuální přístup plný pokory a respektu. Ve své praxi
			čerpám kromě univerzitních poznatků také ze zkušeností z předchozího pracovního poměru. Dále
			se neustále vzdělávám formou kurzů a workshopů. Díky nekonečnému přísunu nové literatury takto
			obohacuji své obzory o nové techniky, metody a informace. Aktivně se věnuji dobrovolnickým
			aktivitám v oblasti psychologie. Docházím pravidelně na supervize a terapie.
		</p>
	</div>
	<div class="w-full flex justify-end mt-5">
		<TextLink href="o-mne">Chci vědět víc</TextLink>
	</div>
</div>
<CardContainer {cards} />
<div class="bg-white rounded-[30px] w-full px-10 py-8 mt-48 mb-44">
	<Heading2>Poděkování</Heading2>
	<div class="text-justify text-xdarkgray">
		<p>
			Založit si vlastní praxi není vůbec jednoduchou záležitostí. Je potřeba mít mnoho znalostí,
			dovedností, vytrvalosti při zajišťování administrativních úkonů a hlavně mít kolem sebe milé,
			podporující a přející lidi.
		</p>
		<p class="mt-3">
			Na tomto místě bych ráda poděkovala
			<Anchor href="https://sylvienavarova.cz/" external>PhDr. Sylvii Navarové</Anchor>, která se
			ujala mého odborného vedení a byla ochotná mne podpořit při administrativních krocích na této
			mé cestě. Další díky bezesporu patří Davidu Tomanovi. Ten nezištně vytvořil krásné logo, které
			zdobí mé stránky, vizitky, razítko i cedulku u poradny. Za podporu děkuji Adél Hudečkové,
			Beátě Linhartové a Jakubu Rubešovi, protože tato jejich podpora mi pomohla odhodlat se a
			naplnit můj sen o vlastní praxi. Nemalé poděkování si zaslouží také můj partner za to, že
			naprogramoval celé stránky a trpělivě vyhovoval mým změnám a požadavkům.
		</p>
		<p class="mt-3">
			A poslední díky plné vděčnosti posílám také do úžasných vydavatelství Pasparta a Portál, které
			mi neustále zasílají nové a zajímavé odborné publikace. Tím podporují nejen mou touhu po
			poznání, ale také rozšiřují portfolio mých technik a metod, které v praxi mohu využívat.
		</p>
	</div>
	<div class="flex flex-col gap-10 md:flex-row justify-around mt-10">
		<Anchor href="https://www.pasparta.cz/e-shop/" external cls="h-10">
			<img src={PaspartaLogo} alt="Pasparta logo" class="object-contain w-full h-full" />
		</Anchor>
		<Anchor href="https://obchod.portal.cz/" external cls="h-10">
			<img src={PortalLogo} alt="Portál logo" class="object-contain w-full h-full" />
		</Anchor>
	</div>
</div>
