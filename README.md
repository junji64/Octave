# Octave

    
    Octave/Basic Operation
    
        % Basic Operations ========================

        >> 5+6
        >> 3-2
        >> 5*8
        >> 1/2
        >> 2^6
        >> 1 == 2   % false
        >> 1 ~= 2
        >> 1 && 0   % AND
        >> 1 || 0   % OR
        >> xor(1,0)
        >> PS1('>> ');
        >> a = 3
        >> a = 3;   % semicolon suppressing output
        >> b = 'hi';
        >> c = (3 >= 1);
        >> c
        >> a = pi;
        >> a
        >> disp(a);
        >> disp(sprintf('2 decimals: %0.2f',a))
        >> disp(sprintf('6 decimals: %0.6f',a))
        >> a 
        >> format long
        >> a
        >> format short
        >> a
        >> A = [1 2; 3 4; 5 6]
        >> A = [1 2;
        > 3 4:
        > 5 6]
        >> v = [1 2 3]
        >> v = [1; 2; 3]
        >> v = 1:0.1:2 
        >> v = 1:6
        >> ones(2,3)
        >> C = 2*ones(2,3)
        >> C = [ 2 2 2; 2 2 2]
        >> W = ones(1,3)
        >> W = zeros(1,3)
        >> W = rand(1,3)
        >> rand(3,3) 	% Uniform distribution
        >> rand(3,3)
        >> rand(3,3)
        >> W = randn(1,3)   % Normal distribution
        >> W = -6 + sqrt(10)*(randn(1,1000));
        >> W 
        >> %
        >> graphics_toolkit('gnuplot')   % this makes graphics work fine ^^
        >> % make change it in octaverc file in "C:\Octave\Octave-4.0.0\share\octave\site\m\startup"
        >> hist(W)
        >> hist(W,50)
        >> eye(4)
        >> I = eye(4)
        >> I = eye(6)
        >> eye(3)
        >> help eye
        >> help rand
        >> help help



    Octave/Plotting
    
