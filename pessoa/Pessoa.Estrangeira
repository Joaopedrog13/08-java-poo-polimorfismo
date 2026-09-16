package pessoa;

public class PessoaEstrangeira extends Pessoa {
    private String passaporte;

    public PessoaEstrangeira(String nome, String passaporte) {
        super(nome);
        this.passaporte = passaporte;
    }

    public String getPassaporte() {
        return passaporte;
    }

    public void setPassaporte(String passaporte) {
        this.passaporte = passaporte;
    }

    @Override
    public String getIdentificacao() {
        return "Nome: " + getNome() + " - Passaporte: " + passaporte;
    }
}
