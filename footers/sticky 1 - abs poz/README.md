A position tulajdonság változtatása az egyik mód arra, hogy a footert a lap aljára helyezd. Négy egyszerű lépésre lesz szükséged:

Csomagolj mindent (a footert is beleértve) egy divbe.
Célozd meg ezt a csomagolót (wrapper), és állítsd a minimális magasságát 100vh-ra, illetve alkalmazd rá a position: relative; szabályt.
Utána célozd meg a footert magát, és állítsd a pozícióját absolute-ra, majd mozgasd a wrapper aljára.
A wrappernek adj egy alsó paddinget, ez legyen egyenlő a footer magasságával, hogy a tartalom ne csússzon be a footer alá.