# Table of contents

* [Code of conduct](README.md)
* [Contributing to Bun](CONTRIBUTING.md)
* [README](<README (1).md>)
* [Security Policy](SECURITY.md)
* [.github](.github/README.md)
  * [pull\_request\_template](.github/pull\_request\_template.md)
* [bench](bench/README.md)
  * [Bundler benchmark](bench/bundle/README.md)
  * [expect-to-equal](bench/expect-to-equal/README.md)
  * [Benchmarking hot module reloading](bench/hot-module-reloading/readme.md)
    * [CSS Stress Test](bench/hot-module-reloading/css-stress-test/README.md)
  * [install benchmark](bench/install/README.md)
  * [HTTP request file upload benchmark](bench/stream-file-upload-client/README.md)
  * [websocket-server](bench/websocket-server/README.md)
* [docs](docs/README.md)
  * [benchmarks](docs/benchmarks.md)
  * [bun-flavored-toml](docs/bun-flavored-toml.md)
  * [index](docs/index.md)
  * [installation](docs/installation.md)
  * [quickstart](docs/quickstart.md)
  * [Troubleshooting](docs/troubleshooting.md)
  * [typescript](docs/typescript.md)
  * [upgrading-webkit](docs/upgrading-webkit.md)
  * [api](docs/api/README.md)
    * [binary-data](docs/api/binary-data.md)
    * [console](docs/api/console.md)
    * [dns](docs/api/dns.md)
    * [ffi](docs/api/ffi.md)
    * [file-io](docs/api/file-io.md)
    * [file-system-router](docs/api/file-system-router.md)
    * [file](docs/api/file.md)
    * [glob](docs/api/glob.md)
    * [globals](docs/api/globals.md)
    * [hashing](docs/api/hashing.md)
    * [html-rewriter](docs/api/html-rewriter.md)
    * [http](docs/api/http.md)
    * [import-meta](docs/api/import-meta.md)
    * [node-api](docs/api/node-api.md)
    * [semver](docs/api/semver.md)
    * [spawn](docs/api/spawn.md)
    * [sqlite](docs/api/sqlite.md)
    * [streams](docs/api/streams.md)
    * [tcp](docs/api/tcp.md)
    * [test](docs/api/test.md)
    * [transpiler](docs/api/transpiler.md)
    * [utils](docs/api/utils.md)
    * [websockets](docs/api/websockets.md)
    * [workers](docs/api/workers.md)
  * [bundler](docs/bundler/README.md)
    * [executables](docs/bundler/executables.md)
    * [index](docs/bundler/index.md)
    * [intro](docs/bundler/intro.md)
    * [loaders](docs/bundler/loaders.md)
    * [macros](docs/bundler/macros.md)
    * [plugins](docs/bundler/plugins.md)
    * [vs-esbuild](docs/bundler/vs-esbuild.md)
  * [cli](docs/cli/README.md)
    * [add](docs/cli/add.md)
    * [bun-completions](docs/cli/bun-completions.md)
    * [bun-create](docs/cli/bun-create.md)
    * [bun-dev](docs/cli/bun-dev.md)
    * [bun install](docs/cli/bun-install.md)
    * [bun-upgrade](docs/cli/bun-upgrade.md)
    * [bundler](docs/cli/bundler.md)
    * [bunx](docs/cli/bunx.md)
    * [init](docs/cli/init.md)
    * [install](docs/cli/install.md)
    * [link](docs/cli/link.md)
    * [pm](docs/cli/pm.md)
    * [remove](docs/cli/remove.md)
    * [run](docs/cli/run.md)
    * [test](docs/cli/test.md)
    * [update](docs/cli/update.md)
  * [dev](docs/dev/README.md)
    * [bundev](docs/dev/bundev.md)
    * [cra](docs/dev/cra.md)
    * [css](docs/dev/css.md)
    * [Creating a Discord bot with Bun](docs/dev/discord.md)
  * [ecosystem](docs/ecosystem/README.md)
    * [elysia](docs/ecosystem/elysia.md)
    * [express](docs/ecosystem/express.md)
    * [hono](docs/ecosystem/hono.md)
    * [react](docs/ecosystem/react.md)
    * [stric](docs/ecosystem/stric.md)
  * [install](docs/install/README.md)
    * [cache](docs/install/cache.md)
    * [index](docs/install/index.md)
    * [lifecycle](docs/install/lifecycle.md)
    * [lockfile](docs/install/lockfile.md)
    * [overrides](docs/install/overrides.md)
    * [registries](docs/install/registries.md)
    * [workspaces](docs/install/workspaces.md)
  * [project](docs/project/README.md)
    * [benchmarking](docs/project/benchmarking.md)
    * [building-windows](docs/project/building-windows.md)
    * [contributing](docs/project/contributing.md)
    * [licensing](docs/project/licensing.md)
    * [roadmap](docs/project/roadmap.md)
    * [internals](docs/project/internals/README.md)
      * [build-process-for-ci](docs/project/internals/build-process-for-ci.md)
  * [RFCs](docs/rfcs/README.md)
  * [runtime](docs/runtime/README.md)
    * [autoimport](docs/runtime/autoimport.md)
    * [bun-apis](docs/runtime/bun-apis.md)
    * [bunfig](docs/runtime/bunfig.md)
    * [debugger](docs/runtime/debugger.md)
    * [env](docs/runtime/env.md)
    * [hot](docs/runtime/hot.md)
    * [index](docs/runtime/index.md)
    * [jsx](docs/runtime/jsx.md)
    * [loaders](docs/runtime/loaders.md)
    * [modules](docs/runtime/modules.md)
    * [nodejs-apis](docs/runtime/nodejs-apis.md)
    * [plugins](docs/runtime/plugins.md)
    * [typescript](docs/runtime/typescript.md)
    * [web-apis](docs/runtime/web-apis.md)
  * [test](docs/test/README.md)
    * [coverage](docs/test/coverage.md)
    * [dom](docs/test/dom.md)
    * [hot](docs/test/hot.md)
    * [lifecycle](docs/test/lifecycle.md)
    * [mocks](docs/test/mocks.md)
    * [snapshots](docs/test/snapshots.md)
    * [time](docs/test/time.md)
    * [writing](docs/test/writing.md)
  * [guides](docs/guides/README.md)
    * [binary](docs/guides/binary/README.md)
      * [arraybuffer-to-array](docs/guides/binary/arraybuffer-to-array.md)
      * [arraybuffer-to-blob](docs/guides/binary/arraybuffer-to-blob.md)
      * [arraybuffer-to-buffer](docs/guides/binary/arraybuffer-to-buffer.md)
      * [arraybuffer-to-string](docs/guides/binary/arraybuffer-to-string.md)
      * [arraybuffer-to-typedarray](docs/guides/binary/arraybuffer-to-typedarray.md)
      * [blob-to-arraybuffer](docs/guides/binary/blob-to-arraybuffer.md)
      * [blob-to-dataview](docs/guides/binary/blob-to-dataview.md)
      * [blob-to-stream](docs/guides/binary/blob-to-stream.md)
      * [blob-to-string](docs/guides/binary/blob-to-string.md)
      * [blob-to-typedarray](docs/guides/binary/blob-to-typedarray.md)
      * [buffer-to-arraybuffer](docs/guides/binary/buffer-to-arraybuffer.md)
      * [buffer-to-blob](docs/guides/binary/buffer-to-blob.md)
      * [buffer-to-readablestream](docs/guides/binary/buffer-to-readablestream.md)
      * [buffer-to-string](docs/guides/binary/buffer-to-string.md)
      * [buffer-to-typedarray](docs/guides/binary/buffer-to-typedarray.md)
      * [dataview-to-string](docs/guides/binary/dataview-to-string.md)
      * [typedarray-to-arraybuffer](docs/guides/binary/typedarray-to-arraybuffer.md)
      * [typedarray-to-blob](docs/guides/binary/typedarray-to-blob.md)
      * [typedarray-to-buffer](docs/guides/binary/typedarray-to-buffer.md)
      * [typedarray-to-dataview](docs/guides/binary/typedarray-to-dataview.md)
      * [typedarray-to-readablestream](docs/guides/binary/typedarray-to-readablestream.md)
      * [typedarray-to-string](docs/guides/binary/typedarray-to-string.md)
    * [ecosystem](docs/guides/ecosystem/README.md)
      * [astro](docs/guides/ecosystem/astro.md)
      * [discordjs](docs/guides/ecosystem/discordjs.md)
      * [docker](docs/guides/ecosystem/docker.md)
      * [drizzle](docs/guides/ecosystem/drizzle.md)
      * [edgedb](docs/guides/ecosystem/edgedb.md)
      * [elysia](docs/guides/ecosystem/elysia.md)
      * [express](docs/guides/ecosystem/express.md)
      * [hono](docs/guides/ecosystem/hono.md)
      * [mongoose](docs/guides/ecosystem/mongoose.md)
      * [nextjs](docs/guides/ecosystem/nextjs.md)
      * [nuxt](docs/guides/ecosystem/nuxt.md)
      * [pm2](docs/guides/ecosystem/pm2.md)
      * [prisma](docs/guides/ecosystem/prisma.md)
      * [qwik](docs/guides/ecosystem/qwik.md)
      * [react](docs/guides/ecosystem/react.md)
      * [remix](docs/guides/ecosystem/remix.md)
      * [solidstart](docs/guides/ecosystem/solidstart.md)
      * [ssr-react](docs/guides/ecosystem/ssr-react.md)
      * [stric](docs/guides/ecosystem/stric.md)
      * [sveltekit](docs/guides/ecosystem/sveltekit.md)
      * [systemd](docs/guides/ecosystem/systemd.md)
      * [vite](docs/guides/ecosystem/vite.md)
    * [http](docs/guides/http/README.md)
      * [fetch](docs/guides/http/fetch.md)
      * [file-uploads](docs/guides/http/file-uploads.md)
      * [hot](docs/guides/http/hot.md)
      * [simple](docs/guides/http/simple.md)
      * [stream-file](docs/guides/http/stream-file.md)
      * [tls](docs/guides/http/tls.md)
    * [install](docs/guides/install/README.md)
      * [add-dev](docs/guides/install/add-dev.md)
      * [add-git](docs/guides/install/add-git.md)
      * [add-optional](docs/guides/install/add-optional.md)
      * [add-peer](docs/guides/install/add-peer.md)
      * [add-tarball](docs/guides/install/add-tarball.md)
      * [add](docs/guides/install/add.md)
      * [azure-artifacts](docs/guides/install/azure-artifacts.md)
      * [cicd](docs/guides/install/cicd.md)
      * [custom-registry](docs/guides/install/custom-registry.md)
      * [jfrog-artifactory](docs/guides/install/jfrog-artifactory.md)
      * [npm-alias](docs/guides/install/npm-alias.md)
      * [registry-scope](docs/guides/install/registry-scope.md)
      * [trusted](docs/guides/install/trusted.md)
      * [workspaces](docs/guides/install/workspaces.md)
      * [yarnlock](docs/guides/install/yarnlock.md)
    * [process](docs/guides/process/README.md)
      * [argv](docs/guides/process/argv.md)
      * [ctrl-c](docs/guides/process/ctrl-c.md)
      * [ipc](docs/guides/process/ipc.md)
      * [nanoseconds](docs/guides/process/nanoseconds.md)
      * [os-signals](docs/guides/process/os-signals.md)
      * [spawn-stderr](docs/guides/process/spawn-stderr.md)
      * [spawn-stdout](docs/guides/process/spawn-stdout.md)
      * [spawn](docs/guides/process/spawn.md)
      * [stdin](docs/guides/process/stdin.md)
    * [read-file](docs/guides/read-file/README.md)
      * [arraybuffer](docs/guides/read-file/arraybuffer.md)
      * [buffer](docs/guides/read-file/buffer.md)
      * [exists](docs/guides/read-file/exists.md)
      * [json](docs/guides/read-file/json.md)
      * [mime](docs/guides/read-file/mime.md)
      * [stream](docs/guides/read-file/stream.md)
      * [string](docs/guides/read-file/string.md)
      * [uint8array](docs/guides/read-file/uint8array.md)
      * [watch](docs/guides/read-file/watch.md)
    * [runtime](docs/guides/runtime/README.md)
      * [cicd](docs/guides/runtime/cicd.md)
      * [import-json](docs/guides/runtime/import-json.md)
      * [import-toml](docs/guides/runtime/import-toml.md)
      * [read-env](docs/guides/runtime/read-env.md)
      * [set-env](docs/guides/runtime/set-env.md)
      * [timezone](docs/guides/runtime/timezone.md)
      * [tsconfig-paths](docs/guides/runtime/tsconfig-paths.md)
      * [typescript](docs/guides/runtime/typescript.md)
      * [vscode-debugger](docs/guides/runtime/vscode-debugger.md)
      * [web-debugger](docs/guides/runtime/web-debugger.md)
    * [streams](docs/guides/streams/README.md)
      * [to-array](docs/guides/streams/to-array.md)
      * [to-arraybuffer](docs/guides/streams/to-arraybuffer.md)
      * [to-blob](docs/guides/streams/to-blob.md)
      * [to-buffer](docs/guides/streams/to-buffer.md)
      * [to-json](docs/guides/streams/to-json.md)
      * [to-string](docs/guides/streams/to-string.md)
      * [to-typedarray](docs/guides/streams/to-typedarray.md)
    * [test](docs/guides/test/README.md)
      * [bail](docs/guides/test/bail.md)
      * [coverage-threshold](docs/guides/test/coverage-threshold.md)
      * [coverage](docs/guides/test/coverage.md)
      * [happy-dom](docs/guides/test/happy-dom.md)
      * [migrate-from-jest](docs/guides/test/migrate-from-jest.md)
      * [mock-clock](docs/guides/test/mock-clock.md)
      * [mock-functions](docs/guides/test/mock-functions.md)
      * [rerun-each](docs/guides/test/rerun-each.md)
      * [run-tests](docs/guides/test/run-tests.md)
      * [skip-tests](docs/guides/test/skip-tests.md)
      * [snapshot](docs/guides/test/snapshot.md)
      * [spy-on](docs/guides/test/spy-on.md)
      * [timeout](docs/guides/test/timeout.md)
      * [todo-tests](docs/guides/test/todo-tests.md)
      * [update-snapshots](docs/guides/test/update-snapshots.md)
      * [watch-mode](docs/guides/test/watch-mode.md)
    * [util](docs/guides/util/README.md)
      * [base64](docs/guides/util/base64.md)
      * [deep-equals](docs/guides/util/deep-equals.md)
      * [deflate](docs/guides/util/deflate.md)
      * [detect-bun](docs/guides/util/detect-bun.md)
      * [entrypoint](docs/guides/util/entrypoint.md)
      * [escape-html](docs/guides/util/escape-html.md)
      * [file-url-to-path](docs/guides/util/file-url-to-path.md)
      * [gzip](docs/guides/util/gzip.md)
      * [hash-a-password](docs/guides/util/hash-a-password.md)
      * [import-meta-dir](docs/guides/util/import-meta-dir.md)
      * [import-meta-file](docs/guides/util/import-meta-file.md)
      * [import-meta-path](docs/guides/util/import-meta-path.md)
      * [main](docs/guides/util/main.md)
      * [path-to-file-url](docs/guides/util/path-to-file-url.md)
      * [sleep](docs/guides/util/sleep.md)
      * [version](docs/guides/util/version.md)
    * [websocket](docs/guides/websocket/README.md)
      * [compression](docs/guides/websocket/compression.md)
      * [context](docs/guides/websocket/context.md)
      * [pubsub](docs/guides/websocket/pubsub.md)
      * [simple](docs/guides/websocket/simple.md)
      * [upgrade](docs/guides/websocket/upgrade.md)
    * [write-file](docs/guides/write-file/README.md)
      * [append](docs/guides/write-file/append.md)
      * [basic](docs/guides/write-file/basic.md)
      * [blob](docs/guides/write-file/blob.md)
      * [cat](docs/guides/write-file/cat.md)
      * [file-cp](docs/guides/write-file/file-cp.md)
      * [filesink](docs/guides/write-file/filesink.md)
      * [response](docs/guides/write-file/response.md)
      * [stdout](docs/guides/write-file/stdout.md)
      * [stream](docs/guides/write-file/stream.md)
      * [unlink](docs/guides/write-file/unlink.md)
* [Tests](test/README.md)
  * [bundler](test/bundler/README.md)
    * [expectBundled](test/bundler/expectBundled.md)
  * [integration](test/integration/README.md)
    * [next](test/integration/next/README.md)
      * [default-pages-dir](test/integration/next/default-pages-dir/README.md)
  * [js](test/js/README.md)
    * [third\_party](test/js/third\_party/README.md)
      * [es-module-lexer test](test/js/third\_party/es-module-lexer/README.md)
  * [cli](test/cli/README.md)
    * [install](test/cli/install/README.md)
      * [migration](test/cli/install/migration/README.md)
        * [complex-workspace](test/cli/install/migration/complex-workspace/readme.md)
* [packages](packages/README.md)
  * [bun-debug-adapter-protocol](packages/bun-debug-adapter-protocol/README.md)
  * [bun-error](packages/bun-error/readme.md)
  * [bun-devtools-frontend](packages/bun-inspector-frontend/README.md)
  * [bun-inspector-protocol](packages/bun-inspector-protocol/README.md)
  * [bun-lambda](packages/bun-lambda/README.md)
  * [bun-plugin-css](packages/bun-plugin-css/README.md)
  * [bun-plugin-lightningcss](packages/bun-plugin-lightningcss/README.md)
  * [bun-plugin-mdx](packages/bun-plugin-mdx/README.md)
  * [bun-plugin-server-components](packages/bun-plugin-server-components/README.md)
  * [bun-plugin-yaml](packages/bun-plugin-yaml/README.md)
  * [Bun APIs Polyfills](packages/bun-polyfills/README.md)
  * [bun-release](packages/bun-release/README.md)
    * [npm](packages/bun-release/npm/README.md)
      * [Bun](packages/bun-release/npm/bun/README.md)
      * [@oven](packages/bun-release/npm/@oven/README.md)
        * [Bun](packages/bun-release/npm/@oven/bun-darwin-aarch64/README.md)
        * [Bun](packages/bun-release/npm/@oven/bun-darwin-x64-baseline/README.md)
        * [Bun](packages/bun-release/npm/@oven/bun-darwin-x64/README.md)
        * [Bun](packages/bun-release/npm/@oven/bun-linux-aarch64/README.md)
        * [Bun](packages/bun-release/npm/@oven/bun-linux-x64-baseline/README.md)
        * [Bun](packages/bun-release/npm/@oven/bun-linux-x64/README.md)
  * [bun-types](packages/bun-types/README.md)
  * [Bun's fork of uSockets](packages/bun-usockets/README.md)
    * [misc](packages/bun-usockets/misc/README.md)
      * [manual](packages/bun-usockets/misc/manual.md)
  * [Bun's fork of uWebSockets](packages/bun-uws/README.md)
    * [Benchmark-driven development](packages/bun-uws/benchmarks/README.md)
    * [uWS Cluster](packages/bun-uws/cluster/README.md)
    * [Examples](packages/bun-uws/examples/README.md)
    * [Fuzz-testing of various parsers, mocked examples and system libraries](packages/bun-uws/fuzzing/README.md)
      * [libEpollFuzzer - fuzzing for Linux servers](packages/bun-uws/fuzzing/libEpollFuzzer/README.md)
      * [seed-corpus](packages/bun-uws/fuzzing/seed-corpus/README.md)
    * [misc](packages/bun-uws/misc/README.md)
      * [µWebSockets v19 user manual](packages/bun-uws/misc/READMORE.md)
    * [Testing](packages/bun-uws/tests/README.md)
  * [Bun for Visual Studio Code](packages/bun-vscode/README.md)
* [src](src/README.md)
  * [cli](src/cli/README.md)
    * [{\[name\]s}](src/cli/README-for-init.md)
  * [JS Modules](src/js/README.md)
    * [internal](src/js/internal/README.md)
      * [node-inspect-extracted](src/js/internal/util/README.md)
  * [deps](src/deps/README.md)
    * [Brotli 1.1.0](src/deps/brotli/README.md)
    * [Zig Datetime](src/deps/zig-datetime/README.md)