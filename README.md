import static org.junit.Assert.assertEquals;
import org.junit.Test;

public class CalculatorTest {

    @Test
    public void testSum() {
        assertEquals(5.0, Calculator.sum(2.0, 3.0), 0.0001);
        assertEquals(0.0, Calculator.sum(-1.0, 1.0), 0.0001);
        assertEquals(-5.0, Calculator.sum(-2.0, -3.0), 0.0001);
    }
}
