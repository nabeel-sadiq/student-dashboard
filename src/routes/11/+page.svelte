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
      title="11th Urdu Theory"
      description="11th urdu theory model paper"
      link="/"
    />
    <Card
      title="11th English Theory"
      description="11th english theory model paper"
      link="/"
    />
    <Card
      title="11th Islamiyat Theory"
      description="11th islamiyat theory model paper"
      link="/"
    />
    <Card
      title="11th Pak. Studies Theory"
      description="11th pak.st theory model paper"
      link="/"
    />
    <Card
      title="11th Chemistry Theory"
      description="11th chemistry theory model paper"
      link="/"
    />
    <Card
      title="11th Biology Theory"
      description="11th biology theory model paper"
      link="/"
    />
    <Card
      title="11th Physics Theory"
      description="11th physics theory model paper"
      link="/"
    />
    <Card
      title="11th Maths Theory"
      description="11th maths theory model paper"
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
      title="11th Chemistry practical"
      description="11th chemistry practical model paper"
      link="/"
    />
    <Card
      title="11th Biology Practical"
      description="11th biology practical model paper"
      link="/"
    />
    <Card
      title="11th Physics Practical"
      description="11th physics practical model paper"
      link="/"
    />
    <Card
      title="11th Computer Practical"
      description="11th computer practical model paper"
      link="/"
    />
  </div>
  
  <Footer />
  