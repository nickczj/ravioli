<template>
  <div>
    <Logos mb-6 />
    <Suspense>
      <div text-gray:80>
        An opionated view on the future of software engineering.
      </div>
      <template #fallback>
        <div op50 italic>
          <span animate-pulse>Loading...</span>
        </div>
      </template>
    </Suspense>
  </div>
</template>
