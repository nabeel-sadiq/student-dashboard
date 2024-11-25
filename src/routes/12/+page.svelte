<script>
    import Sidebar from "../../components/Sidebar.svelte";
    import Card from "../../components/Card.svelte";
    import Select from "../../components/Select.svelte";
    import Footer from "../../components/Footer.svelte";
    import Downbar from "../../components/Downbar.svelte";
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
      link="/"
    />
    <Card
      title="12th English Theory"
      description="12th english theory model paper"
      link="/"
    />
    <Card
      title="12th Islamiyat Theory"
      description="12th islamiyat theory model paper"
      link="/"
    />
    <Card
      title="12th Pak. Studies Theory"
      description="12th pak.st theory model paper"
      link="/"
    />
    <Card
      title="12th Chemistry Theory"
      description="12th chemistry theory model paper"
      link="/"
    />
    <Card
      title="12th Biology Theory"
      description="12th biology theory model paper"
      link="/"
    />
    <Card
      title="12th Physics Theory"
      description="12th physics theory model paper"
      link="/"
    />
    <Card
      title="12th Maths Theory"
      description="12th maths theory model paper"
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
      title="12th Chemistry practical"
      description="12th chemistry practical model paper"
      link="/"
    />
    <Card
      title="12th Biology Practical"
      description="12th biology practical model paper"
      link="/"
    />
    <Card
      title="12th Physics Practical"
      description="12th physics practical model paper"
      link="/"
    />
    <Card
      title="12th Computer Practical"
      description="12th computer practical model paper"
      link="/"
    />
  </div>
  
  <Footer />
  