<script>
	import { Paragraph, Heading3, Anchor } from '$lib';
	import EducationIcon from '$lib/assets/educationIcon.svg';
	import groupIcon from '$lib/assets/group.svg';
	import whiteboardIcon from '$lib/assets/whiteboard.svg';
	import { titleStore } from '../store';

	import yinyogaImg from '$lib/assets/yin_yoga.png';
	import bcdiplomImg from '$lib/assets/bc_diplom.png';
	import relaxaceImg from '$lib/assets/relaxace.png';
	import acterasmusImg from '$lib/assets/ACT_Erasmus.png';
	import emocnileadershipImg from '$lib/assets/emocni_leadership.png';
	import koucImg from '$lib/assets/kouc.png';
	import projevretorikaImg from '$lib/assets/projev_retorika.png';
	import traumapristupImg from '$lib/assets/trauma_respektujici_pristup_SOFA.pdf';
	import dementiaImg from '$lib/assets/Understanding_Dementia_2023_11_Certificate_Kristyna_Sznapkova.pdf';

	titleStore.set('O mně');
</script>

<Paragraph>
	Svou kariéru jsem začala jako vývojář software. Během své cesty jsem vystřídala ohromné množství
	pozic a dlouho jsem nemohla najít takovou, která by mne opravdu bavila a naplňovala. Při
	manažerském postu jsem zjistila, že naslouchání lidem a jejich vedení je mi velmi blízké. Díky
	vzdělávání zaměstnanců jsem se dotkla základů psychologie, které mi naprosto učarovaly, a já se
	rozhodla nastoupit na univerzitu. Postupně jsem se tak propracovala k vývoji lidské duše, protože
	komunikace s lidmi je mi mnohem bližší než komunikace se stroji. Lidské příběhy jsou jako hvězdy
	ve vesmíru - každá je jiná a každá je unikátní. Proto ke každému klientovi zaujímám individuální
	přístup plný pokory a respektu.
</Paragraph>
<Paragraph>
	Ve své praxi čerpám kromě univerzitních poznatků také ze zkušeností z předchozího pracovního
	poměru. Dále se neustále vzdělávám formou kurzů a workshopů. Díky nekonečnému přísunu nové
	literatury takto obohacuji své obzory o nové techniky, metody a informace. Aktivně se věnuji
	dobrovolnickým aktivitám v oblasti psychologie. Docházím pravidelně na supervize a terapie.
</Paragraph>
<Heading3>
	<div class="flex items-center gap-2">
		<img src={EducationIcon} alt="" class="w-8" />Vzdělání
	</div>
</Heading3>
<table class="text-lg border-separate border-spacing-2 lg:border-spacing-4">
	<tbody>
		<tr>
			<td class="align-top font-bold">2023–2025</td>
			<td>
				Magisterské studium psychologie se zaměřením na klinickou psychologii a psychologii
				osobnosti na univerzitě Humanitas s pobočkou ve Vsetíně.
			</td>
		</tr>
		<tr>
			<td class="align-top font-bold">2020–2023</td>
			<td>
				Bakalářské studium psychologie na univerzitě Humanitas, která má svou pobočku ve Vsetíně.
				<Anchor href={bcdiplomImg} external>Získaný titul lic.</Anchor> je ekvivalentem českého Bc. na
				základě Lisabonské úmluvy. Více informací o uznávání zahraničního titulu v České republice <Anchor
					href="https://www.zakonyprolidi.cz/ms/2006-104/zneni-20061101"
					external>ZDE</Anchor
				>.
			</td>
		</tr>
	</tbody>
</table>
<Heading3>
	<div class="flex items-center gap-2">
		<img src={whiteboardIcon} alt="" class="w-8" />
		Kurzy, semináře, výcviky
	</div>
</Heading3>
<table class="text-lg border-separate border-spacing-2 lg:border-spacing-4">
	<tbody>
		<tr>
			<td class="align-top font-bold">01/2024–nyní</td>
			<td>Roční výcvik v ACTu - Terapie přijetí a odhodlání (Institut ACT+; 248 hodin)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">05/2024</td>
			<td>Fairytale Therapy (Erasmus+ Training program; 56 hodin)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">04/2024</td>
			<td
				><Anchor href={koucImg} external>INTECO: Integrativní kouč</Anchor> (Škola manažerského rozvoje;
				230 hodin; Akreditace MŠMT)</td
			>
		</tr>
		<tr>
			<td class="align-top font-bold">03/2024</td>
			<td>Jak reagovat na emoce klienta a první psychická pomoc (Táňa Mančíková; 30 hodin)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">02/2024</td>
			<td>
				<Anchor href={traumapristupImg} external>
					Trauma respektující přístup k řešení náročného chování u dětí
				</Anchor> (SoFA; 16 hodin; Akreditace MŠMT a MPSV)</td
			>
		</tr>
		<tr>
			<td class="align-top font-bold">11/2023</td>
			<td>
				<Anchor href={dementiaImg} external>Understanding Dementia MOOC</Anchor> (University of Tasmania;
				21 hodin)</td
			>
		</tr>
		<tr>
			<td class="align-top font-bold">11/2023</td>
			<td>Health Across the Gender Spectrum (Stanford University e-learning; 2,5 hodiny)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">10/2023</td>
			<td>Introduction to Food and Health (Stanford University e-learning; 2,5 hodiny)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">09/2023</td>
			<td
				><Anchor href={acterasmusImg} external>ACT for your mental health</Anchor> (Erasmus+ Training
				program; 56 hodin)</td
			>
		</tr>
		<tr>
			<td class="align-top font-bold">09/2021</td>
			<td
				><Anchor href={projevretorikaImg} external>Authentic (self)presentation and rhetoric</Anchor
				> (Shine Leadership; 15 hodin)</td
			>
		</tr>
		<tr>
			<td class="align-top font-bold">09/2021</td>
			<td
				><Anchor href={emocnileadershipImg} external>Emotional leadership</Anchor> (Shine Leadership;
				15 hodin)</td
			>
		</tr>
		<tr>
			<td class="align-top font-bold">09/2021</td>
			<td>Difficult conversations (Cadet Start Tietoevry; 16 hodin)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">05/2021</td>
			<td>Managerial basics (Cadet Start Tietoevry; 16 hodin)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">04/2019</td>
			<td
				><Anchor href={relaxaceImg} external>Relaxace, Yoga Nidra a Regresní terapie</Anchor> (Bhavasya
				Yoga School; 22 hodin; Akreditace MŠMT)</td
			>
		</tr>
		<tr>
			<td class="align-top font-bold">04/2019</td>
			<td>
				<Anchor href={yinyogaImg} external>Yin Yoga I.</Anchor> (Monika Winklerová; 18 hodin)
			</td>
		</tr>
	</tbody>
</table>
<Heading3>
	<div class="flex items-center gap-2">
		<img src={groupIcon} alt="" class="w-8" />
		Praxe a zkušenosti
	</div>
</Heading3>
<table class="text-lg border-separate border-spacing-2 lg:border-spacing-4">
	<tbody>
		<tr>
			<td class="align-top font-bold">09/2023–nyní</td>
			<td>PsyHub – Koordinátorka studentského projektu (dobrovolnictví)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">09/2023–nyní</td>
			<td>Terapie tmou – Koordinátorka projektových aktivit (dobrovolnictví)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">07/2023</td>
			<td
				>Mikasa z.s. Ostrava (dobrovolnictví na festivalu Colours of Ostrava v rozsahu 15 hodin)</td
			>
		</tr>
		<tr>
			<td class="align-top font-bold">05–06/2023</td>
			<td>OSU – Administrátor výzkumu (dobrovolnictví v rozsahu 26 hodin)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">04–05/2023</td>
			<td>Anabell z.ú. Ostrava (školní praxe v rozsahu 70 hodin)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">01/2023–nyní</td>
			<td
				>IG PsychoKnihy – Recenze literatury s psychologickou a seberozvojovou tématikou (volný čas)</td
			>
		</tr>
		<tr>
			<td class="align-top font-bold">12/2022–09/2023</td>
			<td>PsyHub – Koordinátorka Literární revue (dobrovolnictví)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">04/2022</td>
			<td>Diagnostický ústav Ostrava-Kunčičky (školní praxe v rozsahu 44 hodin)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">01–02/2021</td>
			<td>Charitní středisko Michala Magone Ostrava – Dubina (školní praxe v rozsahu 36 hodin)</td>
		</tr>
		<tr>
			<td class="align-top font-bold">11/2019–12/2022</td>
			<td>Tietoevry – Vedoucí pozice (3 roky full-time zaměstnání)</td>
		</tr>
	</tbody>
</table>
