[index.html](https://github.com/user-attachments/files/22542666/index.html)
<h1 style="text-align: center;">����� ������� ��������������� �����</h1>
<p style="text-align: center;">����-���� ��������</p>
<h2 style="text-align: center;">��� ����������</h2>
<p style="text-align: center;">� ��� ����:</p>
<ul>
  <li>������� ���</li>
  <li>������� ��� � �������</li>
  <li>������ ����!</li>
</ul>
<p>����������:</p>
<a href="https://web.telegram.org/k/#@somneva" target="_blank">
  <img src="https://picsum.photos/200" alt="����������" style="display:block; margin:0 auto;">
</a>


<p>� ��� ������ �� <a href="https://chatgpt.com/c/68c92587-42c8-8328-8751-c20e35c16c34">Gopota</a></p>

<div style="text-align: center;">
<ul>
  <li>���������</li>
  <li>���</li>
</ul>
</div>

<button id="myButton" onclick="location.reload();">�����</button>

<script>
  let texts = ['�����', '������', '�����', '���', '�������', '���', '�������'];

  function setRandomText() {
    let randomIndex = Math.floor(Math.random() * texts.length);
    document.getElementById('myButton').innerText = texts[randomIndex];
  }

  // ������ ����� ����� ��� �������� ��������
  window.onload = setRandomText;
</script>
