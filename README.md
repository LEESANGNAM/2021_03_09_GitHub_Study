# 2021_03_09_GitHub_Study
<h1>Git Bash Study</h1>
<ul><h2>계정 정보 등록</h2>
	<li>email등록 : git config --global user.email "계정 email"</li>
	<li>계정 등록 : git congfig --global user.name "계정 username"</li>
</ul>
<ul><h2>계정 정보 확인</h2>
	<li>email확인 : git config user.email</li>
	<li>계정확인 : git congfig user.name</li>
</ul>
<ul><h2>도움말(help)</h2>
	<li>도움말 : git help</li>
	<li>특정 명령어 도움말 : git help {명령어}</li>
</ul>
<ul><h2>init</h2>
	<li>해당 폴더를 로컬 저장소로 지정 : git init</li>
</ul>
<ul><h2>Clone</h2>
	<li>해당 저장소를 clone : git clone {git address}</li>
	<li>특정 브랜치만 clone : git clone -b{branch_name} --single-branch {git address}</li>
</ul>
<ul><h2>status</h2>
	<li>워킹트리의 상태확인 : git status</li>
	<li>간결하게 상태확인 : git status -s</li>
</ul>
<ul><h2>add</h2>
	<li>파일 스테이지에 추가 : git add file1 file2...</li>
	<li>변경된 모든 파일 추가 : git add .</li>
</ul>
<ul><h2>reset</h2>
	<li>스테이지에 올린 파일을 스테이지에서 내림 : git reset file1</li>
</ul>
<ul><h2>commit</h2>
	<li>스테이지에 있는 파일 커밋 : git commit</li>
	<li>add를 생략하고 커밋 : git commit -a</li>
	<li>커밋시 메시지 작성 : git commit -m "Message"</li>
</ul>
<ul><h2>log</h2>
	<li>커밋 히스토리 확인 : git log</li>
	<li>최신 n개만 확인 : git log -n{숫자}</li>
	<li>
		<ul>간결하게 확인 : git log --oneline --graph --decorate --all
			<li>--oneline : 커밋 메시지를 한줄로 요약해서 보여줌</li>
			<li>--graph : 커밋 옆애 브랜치의 흐름을 그래프로 보여줌</li>
			<li>--decorate : 브랜치와 태그 등의 참조를 간결히표시</li>
			<li>--all : all 옵션이 없을 경우 HEAD와 관계없는 옵션은 보여주지 않음</li>
		</ul>
	</li>
</ul>
<ul><h2></h2>
	<li></li>
</ul>

