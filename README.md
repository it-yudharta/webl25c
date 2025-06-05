# webl25c

#### buat project baru
1. pastikan sudah install nodejs dan github desktop.
2. buka terminal dan pilih folder tempat project.
3. jalankan `npm create vue@latest`.
4. Project name isi dengan `webl25c`.
5. untuk feature pilih `Router` saja.

##### menjalankan project
1. buka folder `webl25c` di vscode.
2. buka terminal yang ada di vscode dengan ctrl + `.
3. install dependency project dengan menjalankan `npm install` di terminal.
4. jalankan project dengan menjalankan `npm run dev` di terminal.

#### setting github di vscode
1. buat repository di github dengan nama repo `webl25c`.
2. masuk ke menu source controle di github dan pilih `initialize repository`.
3. masukkan `README.md` ke stage dan commit.
4. tambahkan remote github.
5. publish/push/sync ke github.

#### setting cloudflare
1. install wrangler dan cloudflare/vite-plugin degan menjalankan `npm install -D @cloudflare/vite-plugin wrangler` di terminal.
2. setting cloudflare di `vite.config.js`.
3. buat dan setting `wrangler.jsonc`
4. buat file `index.js` di folder api untuk backend.
