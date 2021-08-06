# Notificacao_Phyton

#Receber notificação

#rodar pip install win10toast

from win10toast import ToastNotifier


def chama_mensagem():

    toast = ToastNotifier()
    return toast.show_toast(

        "Notificação",
        "Olá",      
        duration=3
    )
     
#Pode chamar a função de tempos em tempos ou após uma ação     
print(chama_mensagem())

