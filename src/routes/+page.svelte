<script>
  import Sidebar from "../components/Sidebar.svelte";
  import Card from "../components/Card.svelte";
  import Select from "../components/Select.svelte";
  import Footer from "../components/Footer.svelte";
  import Downbar from "../components/Downbar.svelte";
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
    title="9th Urdu Theory"
    description="9th urdu theory model paper"
    link="/"
  />
  <Card
    title="9th English Theory"
    description="9th english theory model paper"
    link="/"
  />
  <Card
    title="9th Islamiyat Theory"
    description="9th islamiyat theory model paper"
    link="/"
  />
  <Card
    title="9th Pak. Studies Theory"
    description="9th pak.st theory model paper"
    link="/"
  />
  <Card
    title="9th Chemistry Theory"
    description="9th chemistry theory model paper"
    link="/"
  />
  <Card
    title="9th Biology Theory"
    description="9th biology theory model paper"
    link="/"
  />
  <Card
    title="9th Physics Theory"
    description="9th physics theory model paper"
    link="/"
  />
  <Card
    title="9th Maths Theory"
    description="9th maths theory model paper"
    link="/"
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
    title="9th Chemistry practical"
    description="9th chemistry practical model paper"
    link="/"
  />
  <Card
    title="9th Biology Practical"
    description="9th biology practical model paper"
    link="/"
  />
  <Card
    title="9th Physics Practical"
    description="9th physics practical model paper"
    link="/"
  />
  <Card
    title="9th Computer Practical"
    description="9th computer practical model paper"
    link="/"
  />
</div>

<Footer />
