# [NER] — Нэг шөнийн тоглолт

Монголын Counter-Strike тоглогчийн ганц HTML файлтай scroll-кино. GLSL/WebGL shader нь үүлэрхэг тэнгэр, жаргах нар, процедурын манхан, шөнийн оддыг зурна. WebGL боломжгүй үед CSS дэвсгэр автоматаар харагдана. Хэсгүүдийг scroll-оор тогтоож, текстийг үг үгээр ил гаргахад GSAP/ScrollTrigger; smooth scroll-д Lenis ашиглана. Хөдөлгөөнийг багасгах тохиргоог хүндэтгэнэ.

## Өөрчлөх

`index.html`-ийн эхэнд байгаа `CONFIG` объектод `name`, `tagline`, `steam`, `instagram`, `facebook`-ийг өөрчилнө. Хуудасны Монгол бичвэрүүдийг `main` хэсэг дотор засна.

## Хостлох

`index.html`-ийг GitHub Pages эсвэл өөр HTTPS статик хостингт байршуулж болно. GitHub Pages-д **Settings → Pages** хэсгээс `main` салбарын үндсэн хавтсыг сонгоно. Фонт, GSAP болон ScrollTrigger нь CDNJS болон Google Fonts-оос; Lenis 1.1.18 нь CDNJS-д байхгүй тул pinned jsDelivr хаягаас ачаалагдана. CDN/WebGL байхгүй байсан ч CSS fallback ба хуудасны үндсэн агуулга харагдана.
