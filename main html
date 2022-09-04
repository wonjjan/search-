<h1>검색창</h1>
<br><br>

<form method="post">
    {% csrf_token %}
    <select name="choose">
        <option value="" selected>사이트 선택</option>
        <option>구글</option>
        <option>유튜브</option>
        <option>네이버</option>
    </select>
    <input type="text" name="comment">
    <button>선택완료</button>
</form>

<a href="{% url 'pot' %}"><button>처음화면</button></a>
<a href="{% url 'delete' %}"><button>검색 비우기</button></a>
