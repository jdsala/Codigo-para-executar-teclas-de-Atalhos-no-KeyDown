//neste Exemplo coloquei um botao Pesquisar e que tambem executa presionando o F7. 

private void FrmPrincipal_KeyDown(object sender, KeyEventArgs e)
        {
            switch (e.KeyData)
            {
                case Keys.F7:
                    tsbPesquisar.PerformClick();
                    break;
                case Keys.F8:
                    tsbGravar.PerformClick();
                    break;
                case Keys.F9:
                    tsbLimpar.PerformClick();
                    break;
                case Keys.F12:
                    tsbVoltar.PerformClick();
                    break;
                default:
                    break;
            }
        }
