# links.darwiz
follow me here!
<footer>
        صفحة روابط Darwizyy19 — مجانية بالكامل
      </footer>
    </div>
  </div>

  <script>
    const pageLinkInput = document.getElementById('pageLink');
    pageLinkInput.value = window.location.href || 'ضع_رابطك_هنا';

    document.getElementById('copyBtn').addEventListener('click', async ()=>{
      try{
        await navigator.clipboard.writeText(pageLinkInput.value);
        alert('تم نسخ الرابط: ' + pageLinkInput.value);
      }catch(e){
        prompt('انسخ الرابط يدويًا:', pageLinkInput.value);
      }
    });
  </script>
</body>
</html>
