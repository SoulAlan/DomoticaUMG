void setup ()
{ 
  Serial.begin (9600); //Iniciamos la comunicación serial.
  pinMode(2,OUTPUT);//Inicializamos los pines que utilizaremos.
  pinMode(3,OUTPUT);
  pinMode(4,OUTPUT); 
  pinMode(5,OUTPUT);
  pinMode(6,OUTPUT);
  pinMode(7,OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(13,OUTPUT);  
} 
void loop ()
{
  if(char dato=Serial.read ()) //Se lee la variable enviada por la APP.
  {
    switch (dato) //Se selecciona el caso dependiendo la variable recibida.
  {
        case 'A':
      {
        digitalWrite(2,HIGH);
        Serial.println("Led encendido");
        break;
      }
    case 'B':
      {
        digitalWrite(2,LOW);
        Serial.println("Led apagado");
        break;
      }
    case 'C':
      {
        digitalWrite(3,HIGH);
        Serial.println("Led encendido");
        break;
      }
    case 'D':
      {
        digitalWrite(3,LOW);
        Serial.println("Led apagado");
        break;
      }
    case 'E':
      {
        digitalWrite(4,HIGH);
        Serial.println("Led encendido");
        break;
      }
    case 'F':
      {
        digitalWrite(4,LOW);
        Serial.println("Led apagado");
        break;
      }
    case 'G':
      {
        digitalWrite(5,HIGH);
        Serial.println("Led encendido");
        break;
      }
    case 'H':
      {
        digitalWrite(5,LOW);
        Serial.println("Led apagado");
        break;
      }
    case 'I':
      {
        digitalWrite(6,HIGH);
        Serial.println("Led encendido");
        break;
      }
    case 'J':
      {
        digitalWrite(6,LOW);
        Serial.println("Led apagado");
        break;
      }
    case 'K':
      {
        digitalWrite(7,HIGH);
        Serial.println("Led encendido");
        break;
      }
    case 'L':
      {
        digitalWrite(7,LOW);
        Serial.println("Led apagado");
        break;
      }
    case 'M':
      {
        digitalWrite(8,HIGH);
        Serial.println("Led encendido");
        break;
      }
    case 'N':
      {
        digitalWrite(8,LOW);
        Serial.println("Led apagado");
        break;
      }
    case 'O':
      {
        digitalWrite(9,HIGH);
        Serial.println("Led encendido");
        break;
      }
    case 'P':
      {
        digitalWrite(9,LOW);
        Serial.println("Led apagado");
        break;
      }
      case 'Q':
      {
        digitalWrite(10,HIGH);
        Serial.println("Led encendido");
        break;
      }
    case 'R':
      {
        digitalWrite(10,LOW);
        Serial.println("Led apagado");
        break;
      }
      case 'S':
      {
        digitalWrite(11,HIGH);
        Serial.println("Led encendido");
        break;
      }
    case 'T':
      {
        digitalWrite(11,LOW);
        Serial.println("Led apagado");
        break;
      }
      case 'U':
      {
        digitalWrite(12,HIGH);
        Serial.println("Led encendido");
        break;
      }
    case 'V':
      {
        digitalWrite(12,LOW);
        Serial.println("Led apagado ");
        break;
      }
      case 'W':
      {
        digitalWrite(13,HIGH);
        Serial.println("Led encendido");
        break;
      }
    case 'X':
      {
        digitalWrite(13,LOW);
        Serial.println("Led apagado");
        break;
      }
      
  }
}
}
