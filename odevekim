from PyQt4.QtGui import *
from PyQt4.QtCore import *
class tabloOrnegi(QDialog):
    def __init__(self,ebeveyn=None):
        super(tabloOrnegi,self).__init__(ebeveyn)
        grid=QGridLayout()
        self.tablo=QTableWidget()
        self.tablo.resize(200,400)
        self.tablo.setRowCount(4)
        self.tablo.setColumnCount(3)
        grid.addWidget(self.tablo)
        item=QTableWidgetItem()
        item.setData(Qt.EditRole,"Adı")
        self.tablo.setItem(0,0,QTableWidgetItem(item))
        self.tablo.setItem(0,1,QTableWidgetItem("Soyadı"))
        self.tablo.setItem(0,2,QTableWidgetItem("Bölüm"))
        self.tablo.setItem(1,0,QTableWidgetItem("Can"))
        self.tablo.setItem(1,1,QTableWidgetItem("Aydın"))
        self.tablo.setItem(1,2,QTableWidgetItem("YBS"))
        self.tablo.setItem(2,0,QTableWidgetItem("Semih"))
        self.tablo.setItem(2,1,QTableWidgetItem("Yarar"))
        self.tablo.setItem(2,2,QTableWidgetItem("YBS"))
        self.tablo.setItem(3,0,QTableWidgetItem("Büşra"))
        self.tablo.setItem(3,1,QTableWidgetItem("Demirgüreşçi"))
        self.tablo.setItem(3,2,QTableWidgetItem("İktisat"))
        self.tablo.show()
        return uyg.exec_()
class tabloListeOrnegi(QDialog):
    def __init__(self,ebeveyn=None):
        super(tabloOrnegi,self).__init__(ebeveyn)
uyg=QApplication([])
pencere=tabloOrnegi()
pencere.show()
uyg.exec_
