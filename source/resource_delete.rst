.. _ngcom_resource_delete:

Как удалять данные
======================================

:ref:`Веб ГИС <ngcom_description>` позволяет удалять загруженные и подключенные в нее данные путем удаления соответствующих ресурсов (:ref:`Векторных слоев <ngcom_vector_layer>`, :ref:`Растровых слоев <ngcom_raster_layer>`, :ref:`Слоев PostGIS <ngcom_postgis_layer>`, :ref:`Слоев WMS <ngcom_postgis_layer>`). 

Чтобы удалить ресурс:

#. Откройте окно свойств ресурса, который вы хотите удалить;
#. Выберите :menuselection:`Действие --> Удалить` на правой панели :ref:`веб-интерфейса <ngw_admin_interface>` Веб ГИС;
#. В открывшемся окне на вкладке :guilabel:`Удалить ресурс` поставьте галочку в строке :guilabel:`Подтвердить удаление ресурса`;
#. Нажмите кнопку :guilabel:`Удалить`. Если ресурс успешно удален, то информация о нем исчезнет из соответствующей :ref:`Группы ресурсов <ngcom_resources_group>`.

.. note:: 
	Аналогичным образом из Веб ГИС можно удалять и иные ресурсы (:ref:`Соединения PostGIS <ngcom_postgis_connect>` и :ref:`Соединения WMS <ngcom_wms_connect>`, :ref:`Сервисы <ngcom_data_services>`, :ref:`Стили <ngcom_styles>`, :ref:`Группы ресурсов <ngcom_resources_group>`).

.. note:: 
	Вы также можете удалять ресурсы из Веб ГИС :ref:`с помощью настольного приложения NextGIS QGIS <ngcom_ngqgis_connect_resource_delete>`.