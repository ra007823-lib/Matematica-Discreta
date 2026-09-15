import javax.swing.JOptionPane;

public class calcMMcMDc {

	public static void main(String[] args) {

		int num1, num2, aux, base1, base2;

		num1 = Integer.parseInt(
				JOptionPane.showInputDialog("Digite o primeiro numero:")
		);

		num2 = Integer.parseInt(
				JOptionPane.showInputDialog("Digite o segundo numero:")
		);
		base1 = num1;
		base2 = num2;

		if (num1 > num2) {

			while (num2 != 0) {

				aux = num1;
				num1 = num2;
				num2 = aux % num2;
			}

		} else {

			while (num1 != 0) {

				aux = num2;
				num2 = num1;
				num1 = aux % num1;
			}
		}
		int mmc = (base1+base2)/num1;
		JOptionPane.showMessageDialog(null, "O MDC é: " + num1 + "O MMC é: "+mmc);
	}
}