<script>
  import "../app.css";
  import { page } from "$app/stores";
  let person = $page.url.searchParams.get("name");
</script>

<div class="bg-slate-200">
  <div
    class="min-h-screen text-center flex flex-col justify-center items-center gap-8"
  >
    <h1 class="text-3xl hand-bold text-gray-500">
      <span class="underline">{`${person || ""}`}</span> You are invited to the wedding
      of
    </h1>
    <h1 class="text-6xl hand-regular text-slate-700">
      Yamada Anna<br />&<br />Argana Phangquestian
    </h1>
  </div>
  <div class="flex w-full min-h-screen">
    <div
      class="flex justify-center flex-col md:flex-row items-center flex-1 gap-4"
    >
      <div class="relative">
        <img
          src="/yamada.png"
          alt="Yamada Anna"
          class="w-[400px] h-[600px] object-cover"
        />
        <span
          class="absolute top-0 right-0 rounded-full px-4 py-2 m-4 bg-black text-white text-xs"
          >Yamada Anna</span
        >
      </div>
      <div class="relative">
        <img
          src="/arga.png"
          alt="Argana Phangquestian"
          class="w-[400px] h-[600px] object-cover"
        />
        <span
          class="absolute top-0 right-0 rounded-full px-4 py-2 m-4 bg-black text-white text-xs"
          >Argana Phangquestian</span
        >
      </div>
    </div>
  </div>

  <div class="flex w-full min-h-screen">
    <div
      class="flex justify-center flex-col md:flex-row items-center flex-1 gap-4"
    >
      <div class="flex items-center gap-8 reddit">
        <h1 class="text-lg border-t border-b w-32 text-right pr-2 py-2">
          Monday
        </h1>
        <div class="flex flex-col justify-center items-center gap-2">
          <p class="text-2xl">April</p>
          <h1 class="text-6xl">1</h1>
          <p class="text-2xl">2024</p>
        </div>
        <h1 class="text-lg border-t border-b w-32 text-left pl-2 py-2">
          AT 5 PM
        </h1>
      </div>
      <p class="hand-regular">hehehehehhehhe.........................</p>
    </div>
  </div>
</div>
