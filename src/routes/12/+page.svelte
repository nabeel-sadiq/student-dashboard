<script>
  import Sidebar from "../../components/Sidebar.svelte";
  import Card from "../../components/Card.svelte";
  import Select from "../../components/Select.svelte";
  import Footer from "../../components/Footer.svelte";
  import Downbar from "../../components/Downbar.svelte";

  const theoryLinks = [
    "https://fbise.edu.pk/ModelPaper/2024New/urdu/Final_Assessment_Framework_Model_Question_Paper_Urdu_SSC-I.pdf#page=19",
    "https://fbise.edu.pk/ModelPaper/2024New/english/Final_Assessment_Framework_Model_Question_Paper_English_SSC-I.pdf#page=30",
    "https://fbise.edu.pk/ModelPaper/2024New/islamiyat/Islamiyat%20Model%20Paper%20SSC-I%20(SNC%202022)%20Final.pdf",
    "https://fbise.edu.pk/ModelPaper/2024New/pst/Final_Assessment_Framework_Model_Question_Paper_PakistanStudies_SSC-I.pdf#page=15",
    "https://fbise.edu.pk/ModelPaper/2024New/chemistry/Final_Assessment_Framework_Model_Question_Paper_Chemistry_SSC-I%20Latest.pdf#page=30",
    "https://fbise.edu.pk/ModelPaper/2024New/bio/Final_Assessment_Framework_Model_Question_Paper_Biology_SSC-I.pdf#page=21",
    "https://fbise.edu.pk/ModelPaper/2024New/physics/Final_Assessment_Framework_Model_Question_Paper_Physics_SSC-I.pdf#page=28",
    "https://fbise.edu.pk/ModelPaper/2024New/computer/Final_Assessment_Framework_Model_Question_Paper_ComputerScience_SSC-I.pdf#page=25",
    "https://fbise.edu.pk/ModelPaper/2024New/maths/Final_Assessment_Framework_Model_Question_Paper_Mathematics_SSC-I.pdf#page=17",
  ];

  const practicalLinks = [
    "https://example.com/practical-1",
    "https://example.com/practical-2",
    "https://example.com/practical-3",
    "https://example.com/practical-4",
  ];
</script>

<span class="inline-flex sm:hidden"><Downbar /></span>
<span class="sm:inline-flex hidden"><Sidebar /></span>
<Select />
<h1
  class="text-base-content text-3xl sm:ml-32 font-bold sm:text-left text-center mt-4"
>
  📝 Theory
</h1>
<div
  class="flex gap-6 flex-wrap sm:justify-start justify-center items-center py-12 sm:px-32 px-12"
>
  <Card
    title="12th Urdu Theory"
    description="12th urdu theory model paper"
    link={theoryLinks[0]}
  />
  <Card
    title="12th English Theory"
    description="12th english theory model paper"
    link={theoryLinks[1]}
  />
  <Card
    title="12th Islamiyat Theory"
    description="12th islamiyat theory model paper"
    link={theoryLinks[2]}
  />
  <Card
    title="12th Pak. Studies Theory"
    description="12th pak.st theory model paper"
    link={theoryLinks[3]}
  />
  <Card
    title="12th Chemistry Theory"
    description="12th chemistry theory model paper"
    link={theoryLinks[4]}
  />
  <Card
    title="12th Biology Theory"
    description="12th biology theory model paper"
    link={theoryLinks[5]}
  />
  <Card
    title="12th Physics Theory"
    description="12th physics theory model paper"
    link={theoryLinks[6]}
  />
  <Card
    title="12th Computer Theory"
    description="12th computer theory model paper"
    link={theoryLinks[7]}
  />
  <Card
    title="12th Maths Theory"
    description="12th maths theory model paper"
    link={theoryLinks[8]}
  />
</div>

<h1
  class="text-base-content text-3xl sm:ml-32 font-bold sm:text-left text-center mt-4"
>
  🧪 Practical
</h1>

<div
  class="flex gap-6 flex-wrap sm:justify-start justify-center items-center py-12 sm:px-32 px-12"
>
  <Card
    title="12th Chemistry Practical"
    description="12th chemistry practical model paper"
    link={practicalLinks[0]}
  />
  <Card
    title="12th Biology Practical"
    description="12th biology practical model paper"
    link={practicalLinks[1]}
  />
  <Card
    title="12th Physics Practical"
    description="12th physics practical model paper"
    link={practicalLinks[2]}
  />
  <Card
    title="12th Computer Practical"
    description="12th computer practical model paper"
    link={practicalLinks[3]}
  />
</div>

<Footer />
