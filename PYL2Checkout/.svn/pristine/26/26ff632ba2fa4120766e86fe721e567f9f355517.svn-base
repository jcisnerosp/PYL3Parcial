Imports System.Text
Imports Microsoft.VisualStudio.TestTools.UnitTesting
Imports Ejercicio5
Imports System.Drawing

<TestClass()> Public Class UnitTest1

    <TestMethod()> Public Sub TestCentro()
        Dim esperado = New Point(0, 0)
        Dim conv = New Class1

        Assert.AreEqual(esperado.X, conv.polarToCartesian(0, 0).X, 0.001)
        Assert.AreEqual(esperado.Y, conv.polarToCartesian(0, 0).Y, 0.001)
    End Sub

    <TestMethod()> Public Sub TestCentroRadio4()
        Dim esperado = New Point(4, 0)
        Dim conv = New Class1

        Assert.AreEqual(esperado.X, conv.polarToCartesian(4, 0).X, 0.001)
        Assert.AreEqual(esperado.Y, conv.polarToCartesian(4, 0).Y, 0.001)
    End Sub

    <TestMethod()> Public Sub Test45()
        Dim esperado = New Point(1 / Math.Sqrt(2), 1 / Math.Sqrt(2))
        Dim conv = New Class1

        Assert.AreEqual(esperado.X, conv.polarToCartesian(1, 45).X, 0.001)
        Assert.AreEqual(esperado.Y, conv.polarToCartesian(1, 45).Y, 0.001)
    End Sub

    <TestMethod()> Public Sub Test90()
        Dim esperado = New Point(0, 3)
        Dim conv = New Class1

        Assert.AreEqual(esperado.X, conv.polarToCartesian(3, 90).X, 0.001)
        Assert.AreEqual(esperado.Y, conv.polarToCartesian(3, 90).Y, 0.001)
    End Sub

    <TestMethod()> Public Sub Test150()
        Dim esperado = New Point(-Math.Sqrt(3), 1)
        Dim conv = New Class1

        Assert.AreEqual(esperado.X, conv.polarToCartesian(2, 150).X, 0.001)
        Assert.AreEqual(esperado.Y, conv.polarToCartesian(2, 150).Y, 0.001)
    End Sub

    <TestMethod()> Public Sub Test217()
        Dim esperado = New Point(-4, -3)
        Dim conv = New Class1

        Assert.AreEqual(esperado.X, conv.polarToCartesian(5, 217).X, 0.001)
        Assert.AreEqual(esperado.Y, conv.polarToCartesian(5, 217).Y, 0.001)
    End Sub

    <TestMethod()> Public Sub Test344()
        Dim esperado = New Point(24, -7)
        Dim conv = New Class1

        Assert.AreEqual(esperado.X, conv.polarToCartesian(25, 344).X, 0.001)
        Assert.AreEqual(esperado.Y, conv.polarToCartesian(25, 344).Y, 0.001)
    End Sub

End Class