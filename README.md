# HeaderGroupGridView
a yii extension for grouping header columns into single column
```
$this->widget('ext.HeaderGroupGridView', array(
	'id'=>'user-grid',
	'summaryText'=>'Total {count} data',
	'mergeHeaders'=>array(
		array(
			'name'=>'Realisasi POK Satker',
			'start'=>3, //indeks kolom 3
			'end'=>4, //indeks kolom 4
		),
		array(
			'name'=>'Realisasi KPPN',
			'start'=>5,
			'end'=>6,
		),
	),
	'dataProvider'=>$dataProvider,
	'columns'=>array(
		//array kolom
	),
));
```
