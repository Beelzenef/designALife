# Widgets

Los widgets son los controles de nuestra aplicación. Son instancias de Clases con propiedades que podemos editar.

## Button

No necesitan presentación, la interfaz pulsable más conocida.

## TextView

Cajas de texto no editable, etiquetas para visualizar mensajes.

## EditText

Cajas de texto con diferentes opciones para introducir texto. Con una propiedad podemos definir qué tipo de datos admiten, _inputType_.

```xml
<EditText
                android:id="@+id/edT_URL"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:inputType="textUri"/>
```

Los [posibles tipos de datos](https://stackoverflow.com/a/2712917/6659852) a elegir son:

- none
- text
- textCapCharacters
- textCapWords
- textCapSentences
- textAutoCorrect
- textAutoComplete
- textMultiLine
- textImeMultiLine
- textNoSuggestions
- textUri
- textEmailAddress
- textEmailSubject
- textShortMessage
- textLongMessage
- textPersonName
- textPostalAddress
- textPassword
- textVisiblePassword
- textWebEditText
- textFilter
- textPhonetic
- textWebEmailAddress
- textWebPassword
- number
- numberSigned
- numberDecimal
- numberPassword
- phone
- datetime
- date
- time

## Spinners

Son controles desplegables para elegir entre opciones, los comboboxes que veíamos en C# con Visual Studio.

Sus valores, como marca la guía de estilos para Android, necesita estar en un fichero XML aparte con valores oportunos. Almacenado en el directorio values, un fichero resources que contiene diferentes arrays de string, con un nombre concreto por el cual será referenciado.

```xml
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string-array name="categorias">
        <item>Categoria 1</item>
        <item>Categoria 2</item>
        <item>Categoria 3</item>
    </string-array>
</resources>
```

Y una vez los hemos definido los valores que va a tener, los valores desplegables se añaden mediante la propiedad Entries en su definición como widget. Se referencia mediante @array/nombreArray.

```xml
 <Spinner
                android:id="@+id/spn_Categoria"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginStart="8dp"
                android:entries="@array/categorias"/>
```