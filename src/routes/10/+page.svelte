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
      title="10th Urdu Theory"
      description="10th urdu theory model paper"
      link="/"
    />
    <Card
      title="10th English Theory"
      description="10th english theory model paper"
      link="/"
    />
    <Card
      title="10th Islamiyat Theory"
      description="10th islamiyat theory model paper"
      link="/"
    />
    <Card
      title="10th Pak. Studies Theory"
      description="10th pak.st theory model paper"
      link="/"
    />
    <Card
      title="10th Chemistry Theory"
      description="10th chemistry theory model paper"
      link="/"
    />
    <Card
      title="10th Biology Theory"
      description="10th biology theory model paper"
      link="/"
    />
    <Card
      title="10th Physics Theory"
      description="10th physics theory model paper"
      link="/"
    />
    <Card
      title="10th Maths Theory"
      description="10th maths theory model paper"
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
      title="10th Chemistry practical"
      description="10th chemistry practical model paper"
      link="/"
    />
    <Card
      title="10th Biology Practical"
      description="10th biology practical model paper"
      link="/"
    />
    <Card
      title="10th Physics Practical"
      description="10th physics practical model paper"
      link="/"
    />
    <Card
      title="10th Computer Practical"
      description="10th computer practical model paper"
      link="/"
    />
  </div>
  
  <Footer />
  