# GIT collision example
* code taken from [here](https://github.com/itelligence-cz/LBP-WA-Fiori/commit/d31039ee6e5da6c95e11c3817bed46b7a6e73bba)
```
that.setBusy("busy", true)
	that.doQuery({
		'op' : 'checkAndConfirmONStayDuration',
		'data' : JSON.stringify(aClosing)
}
```

<br/><br/>

1) fetch

![](images/situation1.png)

---

2) merge

![](images/situation2.png)

---

3) push

![](images/situation3.png)

[link](http://git-school.github.io/visualizing-git/#free-remote)
